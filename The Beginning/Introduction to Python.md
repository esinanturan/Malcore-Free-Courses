<p align="center">
    <img src="../.github/img_4.png"/>
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/) in collaboration with the Malcore team: [https://m4lc.io/courses/register](https://m4lc.io/courses/register)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund and registering for Malcore. You can also join the Malcore Discord server here: [https://m4lc.io/courses/discord](https://m4lc.io/courses/discord)

Malcore offers free threat intel in our Discord via their custom designed Discord bot. Join the Discord to discuss this course in further detail or to ask questions.

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)

**NOTE: This course assumes that you have Python installed and can successfully run Python programs.**

# What will be covered?
- [Why Python?](#why-python)
- [Breakdown of syntax](#syntax)
- [Breakdown of data types](#data-types)
- [Control structures](#control-structures)
- [What the f*ck is a function?](#functions)
- [Writing a program](#writing-a-program)
- [That's all there is](#thats-all-there-is-to-it)


# Why Python?
Most of the time you'll probably hear people talking shit about Python or telling you that you should learn another language entirely. Which is fair, there are plenty of programming languages in the world and a lot of them function the exact same way: you write the code, you compile/interpret the code, the code runs and does what you want it to do. So why should you choose Python? Well first of all this course is not an argumentative essay. I personally don't care what you use, but if you're going to use Python here's some key factors of why it's a decent language:

- Easy to learn
  - Python's syntax is pretty straight forward and is designed to be readable and intuitive. Once you grasp it, you can pretty much read any code thrown at you.
- Versatile
  - Python is actually extremely widely used, its compatible with multiple operating systems and architectures, and can basically do anything that any other language can do, including running assembly code directly inline.
- Multiple paradigms
  - Basically this just means that Python can be object-oriented programming (OOP) or functional oriented (using functions over classes)

This course will be designed to teach you the basics of Python and provide you with the basic understanding of it. The hope is that after this course you'll be able to pickup an editor and start coding successfully.

##### NOTE: This course assumes that you have Python preinstalled and have a basic understanding of programming. 

# Syntax

### Variables
To start we should talk about variables. A variable is basically just a piece of code that stores something for later usage. Variable names must be `a-zA-Z` and can contain an underscore (`_`). An example of a Python variable:
```python
# syntax for creating a variable is
# variable_name = value
name = "Malcore"
```
The above provides a decent example of a variable. We created a variable named `name` that equals `=` the string `Malcore`. Now later on down the road we can call that variable by using the variable name `name`. You can also create variables using integers:
```python
age = 5
```
This variable `age` contains the integer: `5`. But what if you want to be able to tell if a variable is `True` or `False`? Well, those are called booleans and look something like this:
```python
is_young = True
is_old = False
```
As you can see we set the variable `is_young` to `True` and the variable `is_old` to `False`. As an added bonus Python inherits it's boolean structure from earlier languages like C, what this means is that booleans are also equal to integers:
```python
print(True + 1)  # True will always equal 1
# 2
print(False + 1)  # False will always equal 0
# 1
True == 1
# True
False == 0
# True
```
So if you're feeling really fancy or just want to piss people off, you can use booleans in place of integers or integers in place of booleans.

### Variable renaming

In Python you can reassign variables to another name. For example:
```python
one = 1
two = 0
one = two
two = one
print(one, two)
# 0 0
```
What we just did was set variable `one` to the integer `1` and set variable `two` to the integer `0` so that `one` equals `1` and `two` equals `0`. Now we set variable `one` to the value of variable `two` (or `0`) and set variable `two` to the new value of variable `one` (which is `0`) we then `print` both variables to display the values. Being able to rename variables dynamically is useful for things like avoiding conflicting names.

### Using variables
As you have already seen above using variables is pretty straight forward, so we will give you an indepth example of variable usage:
```python
# set the variable x to the integer 5
x = 5

# set the variable y to the integer 10
y = 10

# set the variable z to x + y
z = x + y
# => 15

# set the variable a to z + y
a = z + y
# 25

# set the variable b to a + z
b = a + z
# 40

# Rename the variable x to the value of the variable b
x = b
# 40
```
The above provides a good overview of what we have already talked about, including renaming variables. So at the end the variable `x` is equal to the value of the variable `b` which is the integer `40`. 

A cool thing about variables is that you can perform multiple variable assignments on one line of code in multiple different ways:

```python
# set the variables a, b, and c to 1 so that all the variables have the same value
a = b = c = 1

# set the variables a, b, and c on one line to different values 1, 2, and 3
a, b, c = 1, 2, 3
```
This provides a quick way to set variables in line with one another.

### Variables best practices

Of course, with everything there comes rules or "best practices". Before we get into the best practices, I want you to really understand programming is about doing what you want to do. Yes, readable and maintained code is important, but you should never be a slave to the rules. If you find something that works better for you, you should do that instead.

- Variable names should always describe their purpose. If you're adding multiple prices together and the end value is `x` you should set the end value to `total_price` to clearly show what you are trying to accomplish.
- Always use consistent naming conventions. In Python variable name conventions are `snake_case` all lowercase using underscores (`_`) as spaces.

### Print statements
The `print` statement is one of the most used functions in Python. It is a built-in function that allows you to print data to the console, or display output to the user. The print function also can handle unicode characters. It is extremely easy to understand so this section will be short:

```python
age = 5
name = "Malcore"
print(age)
print(name)
```

### Arithmetic syntax

Python has built-in syntax to help with doing math and arithmetic operations. The are as follows:

##### Addition

Addition in Python is pretty straight forward
```python
# set the variable 'a' to the integer 15
a = 15

# set the variable 'b' to the integer 20
b = 20

# set the variable 'result' to 'a' plus 'b'
result = a + b

# print the results
print(result)
# => 35
```

It is also possible to perform addition by adding to an already declared variable:
```python
# set the variable 'result' to 0
result = 0

# set the variable 'a' to 0
a = 10

# set the variable 'b' to 5
b = 5

# add the sum of 'a' plus 'b' to the preset 'result' variable integer
result += (a + b)

# print the results
print(result)
# => 15
```

##### Subtraction

Subtraction, much like addition, is pretty straight forward. You can also perform the same concept as in addition by using a preset variable to subtract from. In this example we will do both:
```python
# set the variable 'result1' to 30
result1 = 30

# set variable 'a' to 10
a = 10

# set variable 'b' to 5
b = 5

# subtract the result of 'a' minus 'b' from the variable 'result1'
result1 -= (a - b)

# print the results
print(result1)
# => 25

# set the variable 'a' to 7 overwriting the current variable 'a'
a = 7

# set the variable 'b' to 3 overwriting the current variable 'b'
b = 3

# set the variable 'result2' to the result of 'a' minus 'b'
result2 = (a - b)

# print the results
print(result2)
# => 4
```

##### Arithmetic syntax table

There are plenty more arithmetic operators but for this course we will not be going into them. Below is a table of all the operators and information about them if you want to understand more:

| operator | use case                                                                                  | example    |
|----------|-------------------------------------------------------------------------------------------|------------|
| `+`      | Adds two numbers                                                                          | `10 + 10`  |
| `-`      | Subtracts two numbers                                                                     | `3 - 1`    |
| `*`      | Multplies two numbers                                                                     | `2 * 2`    |
| `/`      | Divdes the first number by the second number, will return a float                         | `9 / 3`    |
| `//`     | Divides the first number by the second number and rounds down to the nearest whole number | `3 // 2`   |
| `%`      | Returns the remainder of the division between the first and second number                 | `100 % 10` | 
| `**`     | Raises the first number to the power of the second number                                 | `3 ** 3`   | 


# Data types

Python itself has multiple data types. Data types are categories of values (or data) that you can work with in a program. The understanding of data types is crucial for any developer, new or seasoned, to determine what kind of operations can be done on that data. For example, an integer cannot be treated like a string.

#### Numeric
  - Types: ints, floats, complex
    - Ints:
      - Whole numbers without decimal points: `3`
    - Floats:
      - Numbers with decimal points: `3.12`
    - Complex:
      - Numbers that have both real and imaginary parts: `3j`
  - NOTE: Imaginary numbers are denoted by `j` in Python.
#### Strings
  - Types: single line, multi line
    - Single line:
      - A single line string that is between `"` or `'`: `"this is a string" + 'this is also a string'`
    - Multi line:
      - A string that takes up multiple lines between either `"""` or `'''`: 
```python
""" This is 
a multi line 
string """
''' this is 
also a 
multi line string '''
```
  - NOTE: strings are immutable objects. This means that once a string is created, you cannot directly change their characters. However, it is possible to edit strings in line using something like the following:
```python
s = "this is a string"
s.replace("i", "n")
# => 'thns ns a strnng'
```
#### Booleans
  - Types: True, False
    - True:
      - This expression is often used for conditional statements
    - False:
      - Same as `True`
#### List
  - Lists are ordered collections of data and are mutable. This means they can be directly accessed and changed. You create lists using square brackets: `[]`. You might also know these as `arrays`.
```python
nums = [1, 2, 3]
nums.append(4)
print(nums)
# => [1, 2, 3, 4]
nums.pop()
# => 4
print(nums)
# => [1, 2, 3]
```
#### Tuple
  - Tuples are immutable lists, meaning that you cannot directly change them after the element is created
```python
a = (1, 2, 3)
a.append(4)
# Traceback (most recent call last):
#  File "<stdin>", line 1, in <module>
# AttributeError: 'tuple' object has no attribute 'append'
a.add(4)
# Traceback (most recent call last):
#  File "<stdin>", line 1, in <module>
# AttributeError: 'tuple' object has no attribute 'add'
```
 - NOTE: tuples are used for when the data needs to remain constant and should never be changed
#### Dicts (dictionary)
  - A dict is an unordered collection of key and value pairs. Each key must be unique and are used to access the values associated with them. You call a dict by using: `{}`
```python
my_dict = {'a': 1, 'b': 2, 'c': 3}
print(my_dict['a'])
# => 1
my_dict['d'] = 4
print(my_dict)
# => {'a': 1, 'c': 3, 'b': 2, 'd': 4}
```
#### Set
  - A set is an unordered collection of unique items. There are no duplicates allowed in a set. You create a set by using: `{}` or `set()`
```python
a = {1, 1, 2, 3, 4}
print(a)
# => set([1, 2, 3, 4])
b = set()
b.add(1)
b.add(1)
b.add(2)
print(b)
# => set([1, 2])
```
#### NoneType
  - `None` is a special type that represents the absence of data. Much like `null`. This signifies that something is empty
```python
a = None
print(a == 0)
# => False
print(a == None)
# => True
```

It is possible to determine what type an object is by using the following:
```python
x = 10
print(type(x))
# => <type 'int'>
```

You can also determine if an object is an instance of a type by doing the following:
```python
x = 5j
print(isinstance(x, complex))
# => True
```

These help determine the types and allow you to make decisions based off that type.

# Control structures

Control structures allow you to control the flow of the program based on conditions, repetitions, and other logical indicators. These will help make decisions on what to do with the code.

#### Conditional statements

These allow you to make decisions based on certain conditions:
```python
a = 10 
b = 5

# if the variable 'a' is equal to the variable 'b'
# this can never be True because:
# the variable 'a' is the integer 10
# the variable 'b' is the integer 5
if a == b:
    print("This will never be True")

# if the variable 'a' does not equal the variable 'b'
elif a != b:
    print("This will always be True")

# this can never be called because the above condition is always True
else:
    print("How did we get here?")
```

The above example provides a decent explanation of how conditional statements work. There is not a limit to how many `elif` conditions there can be. 

#### Loops

Loops allow you to execute a block of code multiple times. There are `for` loops and `while` loops. 
- `for` loop
  - This loop iterates of a sequence of data
```python
items = [1, 2, 3]
for i in items:
    print(i)
# 1
# 2
# 3
```
This loop will always stop after the sequence of data is finished. It will run its code block for each sequence of data presented. You can use `lists`, `tuples`, or `strings` with a `for` loop.
- `while` loop
  - This loop continuously runs until the condition set forth is False
```python
count = 10
while count != 0:
    count -= 1
    print(count)
# 9
# 8
# 7
# 6
# 5
# 4
# 3
# 2
# 1
# 0
```
This loop above will subtract 1 from `count` every iteration until `count` does not equal 0. It is worth mentioning that `while` loops can be dangerous. The incorrect condition can create a forever loop that will continuously run and eat resources forever. An example of a forever loop is:
```python
while True:
   print("1")
```
This loop will NEVER end.

Now that we understand the basics of loops we should start talking about how to break out of them earlier, skipping iterations, and loop controls. We will use `for` loops for the remainder of these examples. You should always use `for` loops unless you absolutely have to use a `while` loop (I'm sure I'll get a lot of hate for that, I don't care).

#### Breaking out of loops

To break out of loops you use the `break` statement. This statement allows you to stop the iterations of a loop immediately.
```python
l = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
for i in l:
    if i == 4:
        print("Break the loop")
        break
    else:
       print(i)
# 1
# 2
# 3
# Break the loop
```

The above code shows you exactly how the `break` statement works. It runs through the code until a condition with an `if/else` statement is met, it will then print to the screen and break the iterations.

#### Skipping iterations
To skip iterations all you have to do is use the `continue` or the `pass` statement. The difference between these two statements is that a `pass` statement indicates there is nothing to execute and acts as a type of `nop`. A `continue` statement forcibly skips the iteration of the loop. `pass` is usually used to indicate future code.

Using the `pass` statement:
```python
l = [1, 2, 3, 4, 5]
for i in l:
    pass
# absolutely nothing happens.
```

Using the `continue` statement:
```python
l = [1, 2, 3, 4, 5, 6]
for i in l:
    if i == 3:
        continue
    else:
        print(i)
# 1
# 2
# 4
# 5
# 6
```

#### Loop control

Sometimes in a loop you need to execute something right after the loop finishes normally. When there is no break statement encountered. You can accomplish this by using an `else` in the loop. For example:
```python
l = [1, 2, 3, 4, 5, 6]
for i in l:
    if i == 7:
        print("Break statement hit")
        break
    else:
        print(i)
else:
    print("No break caught")
# 1
# 2
# 3
# 4
# 5
# 6
# No break caught
```

Now if we do the same thing and make the list longer:
```python
l = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
for i in l:
    if i == 7:
        print("Break statement hit")
        break
    else:
        print(i)
else:
    print("No break caught")
# 1
# 2
# 3
# 4
# 5
# 6
# Break statement hit
```

# Functions

A function is a reusable block of code that performs a specific task. They help to organize your code and make it more modular while allowing you to reuse the function itself to perform the same block of code. Functions should solve one problem, and solve it well. The key concepts of a function are: the definition of it (declaring the function), the execution of the function itself (what does it do), the parameters that can be taken by the function (arguments that you can pass to it), the return value (what does the function return if anything). To define a function in Python you use the `def` statement. Here is an example:
```python
def create_list(length=7):
    """ 
    create a list that takes a `length` argument. 
    this length is defaulted to `7` if no argument is passed
    
    this is called a 'keyword' argument 
    """
    # this function returns a list of data the same length as the keyword argument
    return range(length)


def iter_list(l):
    """
    take a list and run a for loop on it to 
    iterate through the list
    
    this is called a 'positional' argument. 
    """
    for piece in l:
        print(piece)


# use the function and keep the keyword argument defaulted at 7
l1 = create_list()

# reuse the same function and change the keyword argument to 15
l2 = create_list(length=15)

# in order to run the `iter_list` function it is required to pass the positional argument
# iterate through the first list by passing the created list to the function
iter_list(l1)
# 0
# 1
# 2
# 3
# 4
# 5
# 6

# reuse the function and iterate through the second list by passing the second list to the function
iter_list(l2)
# 0
# 1
# 2
# 3
# 4
# 5
# 6
# 7
# 8
# 9
# 10
# 11
# 12
# 13
# 14
```
It is worth mentioning that functions can take multiple positional arguments as well as multiple keyword arguments. There are a couple ways to do this:
```python
def arg_func(arg1, arg2, arg3, arg4=4, arg5=5, arg6=6):
    """
    this function takes multiple positional and keyword arguments
    """
    print(arg1, arg2, arg3, arg4, arg5, arg6)


def arg_func_2(*args, **kwargs):
    """
    this function takes multiple positional and keyword arguments
    """
    print(args, kwargs)


arg_func(1, 2, 3)
# (1, 2, 3, 4, 5, 6)
arg_func_2(1, 2, 3, arg4=4, arg5=5, arg6=6)
# ((1, 2, 3), {'arg4': 4, 'arg5': 5, 'arg6': 6})
```
As you can see the `**kwargs` arg is a `dict` where you can access the keyword argument by using the `key`, and the positional arguments are tuple of data.

# Writing a program

Now that you have a basic grasp on how all this works we will write a basic program that incorporates all the information we have gone through. We will be writing a basic calculator:
```python
def add(a, b):
    """
    take two positional arguments and add them together.
    return the value
    """
    return a + b


def subtract(a, b):
    """
    take two positional arguments and subtract them.
    return the value.
    """
    return a - b


def display_menu():
    """
    create a display menu that will show to the user
    this function uses the `\n` or newline character to keep it on one line
    """
    print("select operation:\n1. Add\n2. Subtract\n9. Exit")


def calculator():
    """
    create a main function that will house the logic of the calculator
    """
    # use a forever loop
    while True:
        # display the help menu
        display_menu()

        # get input from the user using the `input` statement
        choice = input("enter your choice: ")

        # since the integers are passed from the console they will be strings
        if choice == '9':
            print("exiting the calculator.")
            # break out of the loop
            break

        # check if the choice is in the list of available options or not
        if choice not in ['1', '2', '9']:
            print("invalid input! please select a valid operation.")
            # continue the process
            continue

        # try to change the arguments from a string to an integer
        try:
            num1 = float(input("enter first number: "))
            num2 = float(input("enter second number: "))
        except ValueError:
            # if it errors out catch the error and throw that its invalid
            print("invalid input! please enter valid numbers.")
            # continue the process
            continue
        
        # these outputs are being formatted using the `f` at the start of the string.
        # this allows you to add variables into the string
        if choice == '1':
            print(f"the result of {num1} + {num2} is: {add(num1, num2)}")
        elif choice == '2':
            print(f"the result of {num1} - {num2} is: {subtract(num1, num2)}")
        else:
            print("invalid option!")
            # no operation
            pass


# this special statement means that if the name of the called program
# is equal to this file, start the process
if __name__ == "__main__":
    # call the main function
    calculator()
```

Let's break down this code to fully understand what is happening:
```python
def add(a, b):
    """
    take two positional arguments and add them together.
    return the value
    """
    return a + b
...
```
This function takes two arguments and adds those two arguments together. For example `add(2, 2)` will equal `4`.

```python
...
def subtract(a, b):
    """
    take two positional arguments and subtract them.
    return the value.
    """
    return a - b
...
```
This function also takes two arguments and subtracts them from one another. For example `subtract(3, 1)` will equal `2`.
```python
...
def display_menu():
    """
    create a display menu that will show to the user
    this function uses the `\n` or newline character to keep it on one line
    """
    print("select operation:\n1. Add\n2. Subtract\n9. Exit")
...
```
This function creates a basic help menu for the user to see by adding newlines it makes it on a single line. 

```python
...
def calculator():
    """
    create a main function that will house the logic of the calculator
    """
    # use a forever loop
    while True:
        # display the help menu
        display_menu()

        # get input from the user using the `input` statement
        choice = input("enter your choice: ")

        # since the integers are passed from the console they will be strings
        if choice == '9':
            print("exiting the calculator.")
            # break out of the loop
            break

        # check if the choice is in the list of available options or not
        if choice not in ['1', '2', '9']:
            print("invalid input! please select a valid operation.")
            # continue the process
            continue

        # try to change the arguments from a string to an integer
        try:
            num1 = float(input("enter first number: "))
            num2 = float(input("enter second number: "))
        except ValueError:
            # if it errors out catch the error and throw that its invalid
            print("invalid input! please enter valid numbers.")
            # continue the process
            continue
        
        # these outputs are being formatted using the `f` at the start of the string.
        # this allows you to add variables into the string
        if choice == '1':
            print(f"the result of {num1} + {num2} is: {add(num1, num2)}")
        elif choice == '2':
            print(f"the result of {num1} - {num2} is: {subtract(num1, num2)}")
        else:
            print("invalid option!")
            # no operation
            pass
...
```
This function is the main logic of the program and has the control flow for the entire program. It has an infinite `while` loop that will never end that wraps all the other logic. The first thing it does is display the help menu and take the users input to take the appropriate action.

---

#### Sponsor

Special thanks to the sponsor of this course! Guided Hacking!

<p align="center">
    <img src="../.github/sponsor_images/gh.png">
</p>

GH is a website devoted to producing high quality educational content related to game hacking, reverse engineering & ethical hacking.

---

# That's all there is to it

That's all there is to it! You have learned the basics of Python and successfully built your own calculator program. We hope this course has given you the basic understandings of programming in Python and you have learned something.

#### Support the Bible

Once again, this course is offered for free by The Perkins Cybersecurity Educational Fund in collaboration with Malcore! If you found this information valuable and want to support the continued development of the Malware Bible please consider:
- Donating to the Malware Bible Fund → [Donate Here](https://donorbox.org/malware-bible-fund)
- Registering for Malcore → [Sign Up](https://m4lc.io/courses/register)
- Joining the Malcore Discord → [Join Today](https://m4lc.io/courses/discord) 

#### Become a sponsor

These courses reach thousands of cybersecurity professionals, researchers, students, and teachers worldwide who actively engage in learning and advancing the field. Sponsoring our educational initiative not only supports free cybersecurity education but also places your brand in front of a highly technical and security-conscious audience.

Interested in partnering? Let's talk about how your organization can be featured in our future courses: [Contact us today!](https://perkinsfund.org/) Please view our [Sponsorship Packages](../.github/sponsorships/sponsorship_package.md) for more details!
