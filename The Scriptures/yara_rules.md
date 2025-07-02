<p align="center">
    <img src="../.github/yara-rules.png">
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund 

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)**

---

# Index

- [Overview](#yara-rule-overview)
- [Keywords and sections](#keywords-and-sections)
- [Import overview](#imports-overview)
- [Meta overview](#meta-overview)
- [Strings overview](#strings-overview)
- [Conditions overview](#conditions-overview)

# Yara rule overview

```
┌───────────────────────────── Rule Header ───────────────────────────────┐
│    ┌──────────────── Imports ───────────────┐                          
│    │  import "pe"                             <- Import modules        
│    └─────────────────────────────────────────┘                          
│                                                                         
│    rule <rule_name> : <tag1> <tag2> ...                                 
│    { [ Start the rule with a open bracket ]                             
│     ┌──────────────── Section: Meta ────────────┐                      
│     │ meta:                                                            
│     │   description = "..."                       <- Freeform comments 
│     │   author = "..."                                                 
│     │   date = "YYYY-MM-DD"                                            
│     └────────────────────────────────────────────┘                      
│                                                                         
│     ┌──────────────── Section: Strings ───────┐                       
│     │ strings:                                                         
│     │   $text1 = "malicious string"              <- Plaintext          
│     │   $hex1  = { 6D 61 6C 77 61 72 65 }        <- Hex pattern        
│     │   $re1   = /evil[\d]+/                     <- Regex pattern      
│     └───────────────────────────────────────────┘                       
│                                                                         
│     ┌───────────── Section: Condition ────────┐                       
│     │ condition:                                                       
│     │   any of them                              <- Trigger logic      
│     │   // other examples:                                             
│     │   all of ($text1, $hex1)                                         
│     │   $re1 and filesize < 1MB                                        
│     └───────────────────────────────────────────┘                       
│   } [ End the rule with a close bracket ]                               
└─────────────────────────────────────────────────────────────────────────┘
```

---

# Keywords and sections

- `import`
  - Use to import modules
- `meta:`
  - Used for comments and metadata, this section is not used in the logic of the rule
- `strings:`
  - Where you define the context you're looking for
- `condition:`
  - Where the logic is defined, you set your condition here to determine matches

---

# Imports overview

Imports allow you to access modules within the Yara framework. To use imports all you have to do is `import "module"` at the start of the rule.

| Module    | Use case examples                          |
|-----------|--------------------------------------------|
| `pe`      | Analyze PE headers, entry point, etc.      |
| `math`    | Use math functions in conditions           |
| `dotnet`  | Gather attributes out of .NET files        |
| `cuckoo`  | Use dynamic analysis from Cuckoo sandbox   |
| `lnk`     | Get lnk file attributes                    |
| `console` | Provides the ability to log to the console |

You can find an exhaustive breakdown [here](https://yara.readthedocs.io/en/stable/modules.html)

---

# Meta overview

Meta sections contain the metadata of the rule and are not used within the logic of the rule. It is filled with key/value pairs and can contain pretty much anything.

```
...
  meta:
   author = "Some Author" 
   copyright = "PCEF"
   something = "something
...
```

---

# Strings overview

This is the section where you create your strings to determine if it is the same file or not. All strings must start with a `$` character. These are used in the conditions section to refer to the string. The strings section is not actually needed to make a complete rule as long as the conditions section doesn't rely on any strings.

```
...
  strings:
    # This is a regular string
    $s1 = "This is a test string"
    
    # This is a hexidecimal string
    # ??            == Any bytes match
    # [1-50         == Indicate a jump from 1 to 5 match
    # ~             == This is a not operator, any value but the defined
    # ~?            == Not operator with an any bytes to indicate any but 
    #                  defined
    # [1-]          == Indicates and unbound jump, there is not an end
    # (90 89 | 12)  == This provides alternatives for the bytes either the 
    #                  first two or the second one
    $s2 = { ?? 90 90 [1-5] ~00 ~?0 [1-] (90 89 | 12) } 
    
    # This is the regular expression. All regular expressions are in the 
    # Perl programming language format.
    $s3 = /some.magic\.regex\"/
    
    # Strings are able to take "modifiers" to make them match more 
    # types of the string. This specific one means that there is 
    # no character case constraint. For example this will match
    # bot 'test string' and 'TEST STRING' and any variation 
    $s4 = "test string" nocase 
...
```

#### Text strings

Text strings are able to contain subsets of the C language escape sequences such as:

| Sequence | Description         |
|----------|---------------------|
| `\"`     | Double quote        |
| `\\`     | Backslash           |
| `\r`     | Carriage return     |
| `\t`     | Tab space           |
| `\n`     | New line            |
| `\xdd`   | Hexadecimal bytes   |

#### Modifiers 

You can also use modifiers for text string as seen in the above example. Modifiers include:

| Modifier   | Description                                                                                                          |
|------------|----------------------------------------------------------------------------------------------------------------------|
| `nocase`   | No character case constraints                                                                                        |
| `wide`     | Matches strings encoded with two up to bytes per character                                                           |
| `ascii`    | Standard ascii characters                                                                                            |
| `xor`      | Single byte Xor applied to the string                                                                                |
| `base64`   | Look for the string in a base64 encoding (`base64wide` exists as well, you can also set the charset of the encoding) |
| `fullword` | Guarantees full word match                                                                                           |
| `private`  | Will never be included in the output of Yara                                                                         |

#### Regular expressions

Regular expressions can take the following metacharacters:

| Meta    | Description                                              |
|---------|----------------------------------------------------------|
| `\`     | Quote the next character                                 |
| `^`     | Match the beginning                                      |
| `.`     | Matches any single character except new lines            |
| `       | Alteration                                               |                                                                               
| `()`    | Group                                                    |
| `[]`    | Set of characters                                        |
| `*`     | Match 0 or more times                                    |
| `+`     | Match 1 or more times                                    |
| `?`     | Match 0 or 1 times                                       |
| `{n}`   | Match exactly n amount times                             |
| `{n,}`  | Match at least n amount times                            |
| `{,n}`  | Match at most n amount times                             |
| `{n,n}` | Match at least n amount times and at most n amount times |
| `\w`    | Alphanumeric word character                              |
| `\W`    | Any non-word character                                   |
| `\s`    | Whitespace character                                     |
| `\S`    | Non-whitespace character                                 |
| `\d`    | Digit character                                          |
| `\D`    | Non-digit character                                      |
| `\b`    | Word boundaries                                          |
| `\B`    | Except at a word boundary                                |

# Conditions overview

Conditions are basically just boolean expressions used to establish if the rule matches your comparison.

```
...
  condition:
   # Three of any of the strings that start with $s
   3 of ($s*) 
...
```

#### Operators


| Meta            | Description                                                         |
|-----------------|---------------------------------------------------------------------|
| `[]`            | Quote the next character                                            |
| `~`             | Bitwise not                                                         |
| `-`             | Subtraction                                                         |
| `.`             | Structure member access                                             |                                                                               
| `*`             | Multiplication                                                      |
| `/`             | Division                                                            |
| `%`             | Remainder                                                           |
| `+`             | Addition                                                            |
| `<<`            | Bitwise left shift                                                  |
| `>>`            | Bitwise right shift                                                 |
| `&`             | Bitwise AND                                                         |
| `^`             | Bitwise XOR                                                         |
| `\|`            | Bitwise OR (minus `\`)                                              |
| `<`             | Less than                                                           |
| `>`             | Greater than                                                        |
| `<=`            | Less than or equal to                                               |
| `>=`            | Greater than or equal to                                            |
| `==`            | Equal to                                                            |
| `!=`            | Not equal to                                                        |
| `[i]contains`   | String contains substring, adding `i` makes it non-case sensitive   |
| `[i]startswith` | String startswith substring, adding `i` makes it non-case sensitive |
| `[i]endswith`   | String ends with substring, adding `i` makes it non-case sensitive  |
| `iequals`       | Non-case sensitive string comparison                                |
| `matches`       | String matches regular expression                                   |
| `not defined`   | Logical NOT check for non-defined expression                        |
| `and`           | Logical AND                                                         |
| `or`            | Logical OR                                                          |
| `filesize`      | Checks the file size                                                |
| `at`            | String offset or virtual address search                             | 
| `entrypoint`    | Special variable to check the Pe or ELF entrypoint (deprecated)     |  

#### Accessing data at specific locations

You may need to access data at a certain locations and read 16, 32, or 64bit integers using an offset, use one of the following to read data from them:

```
int8(<offset or virtual address>)
int16(<offset or virtual address>)
int32(<offset or virtual address>)

uint8(<offset or virtual address>)
uint16(<offset or virtual address>)
uint32(<offset or virtual address>)

int8be(<offset or virtual address>)
int16be(<offset or virtual address>)
int32be(<offset or virtual address>)

uint8be(<offset or virtual address>)
uint16be(<offset or virtual address>)
uint32be(<offset or virtual address>)
```
