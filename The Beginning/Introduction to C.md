<p align="center">
    <img src="../.github/img_5.png" height="512" width="512"/>
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/) in collaboration with the Malcore team: [https://m4lc.io/courses/register](https://m4lc.io/courses/register)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund and registering for Malcore. You can also join the Malcore Discord server here: [https://m4lc.io/courses/discord](https://m4lc.io/courses/discord)

Malcore offers free threat intel in our Discord via their custom designed Discord bot. Join the Discord to discuss this course in further detail or to ask questions.

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

---

#### Sponsor

Special thanks to the sponsor of this course: [QuantAIRAS](https://www.linkedin.com/in/cybertechexec)!

<p align="center">
    <img src="../.github/sponsor_images/qai.png" width="512" height="512">
</p>

QuantAIRAS merges AI and Quantum Computing. Delivering real-time, adaptive cybersecurity to detect threats, counter APT’s, and use social behavior analysis, providing unmatched defense.

---

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)

# What will be covered?

- [What is C?](#what-is-c)
- [C Syntax and Structures](#syntax-and-structures)
- [Control Flows](#controlling-the-flow)
- [C Functions](#c-functions)
- [What the F*ck is a Pointer?](#what-the-fck-is-a-pointer)
- [Memory Overview](#memory-allocation)
- [Preprocessor Directives and Macros](#directives-and-macros)
- [Debugging and Error Handling](#debugging-and-errors-handling)
- [Writing a Program](#write-some-code)
- [That's all!](#thats-all)

---

# What is C?

In a sentence: C is a powerful general-purpose compiled programming language.

In a more descriptive way: C is a powerful compiled programming language that was developed by Dennis Ritchie in 1972 at Bell Labs. It was originally designed for systems programming specifically operating systems. Overtime C became one of the most widely used languages in existence and was used for a lot more than just operating system development. C is known for simplicity, efficiency, and system resource control. It is a popular choice for applications that require high performance or low-level interaction. There are of course issues with C a lot of people consider it a "broken language" however, we will not get into that debate here. 

#### Issues and benefits of C

It is good for you to understand the issues in C as well as the benefits. We will first start with the issues:

- Manual memory management and no garbage collection. Meaning that you must manage your own memory in your programs, it is not done for you like it is in other languages such as Python.
- Lack of object orientation. There is no OOP in C. Meaning it does not have classes in it. 
- There is no built-in error handling. C relies on return codes and external error handling.
- C's low-level access can provide security issues such as buffer overflows, stack overflows, and other security issues. These issues can be exploited if not carefully written.

The issues are descriptive and provide a good understanding of what's wrong with the C language and what can arise for the developer. However, there are of course benefits of C such as:

- Efficiency and speed. C is highly efficient with minimal overhead runtime. Critical performance applications are ideal to write in C due to its direct memory access and low-level operation abilities.
- C is very portable. It can be ported across multiple platforms easily.
- Simplicity. Despite how powerful C is, it is simple. There is a small number of keywords and the syntax is pretty straightforward.
- Extensiveness. There are millions of libraries for C that can do literally anything you can imagine. It's been around long enough that everything has been created.

---

# Syntax and Structures

Now that you actually know what C we is should get into the basics of syntax and data structures. We will go through a breakdown of the syntax:

- Comments:
  - Single line comment example:
```c
// this is a comment in C
```
  - Multi line comment example:
```c
/* 
   this is 
   a 
   multi line
   comment in C
*/
```
- Data types:
  - `int`: integer values, IE: `int x = 5;`
  - `float`: floating point values, IE: `float pi = 3.14;`
  - `double`: double floating point values, IE: `double pi = 3.14159;`
  - `char`: single character, IE: `char letter = 'A';`
  - `void`: signifies no value or empty set of values.
- Variables:
  - Variables must always be declared before use. For example:
```c
int a;
float b;
char c;
```
  - It is also possible to initialize a variable upon use
```c
int a = 5;
char c = 'c';
float b = 1.5;
```
- Constants:
  - You can declare a constant using the `const` keyword. IE: `const int AGE = 33;`
  - You can also declare them using `#define`, IE: `#define PI 3.14`
- Operators:
  - Arithmetic operators:
    - `+` addition
    - `-` subtraction
    - `*` multiplication
    - `/` division
    - `%` modulus
  - Comparison operators:
    - `==` equal to
    - `!=` not equal to
    - `>` greater than
    - `<` less than
    - `>=` greater than or equal to
    - `<=` less than or equal to
  - Logical operators:
    - `&&` logical AND o
    - `||` logical OR 
    - `!` logical NOT 
- Arrays
  - Arrays allow you to store multiple values of the same type, IE: `int numbers[5] = {1,2,3,4,5};`
- Structures (structs):
  - A structure (or struct) is a grouping of different data types. Example:
```c
struct Person {
  char name[50];
  int age;
  float height;
};

// create a person
struct Person john = {.name = "John", .age = 50, .height = 65.6};
```
- Enumerations (enums):
  - An enumeration (enum) is a way to assign names to integer values. Example:
```c
enum Weekday {Monday, Tuesday};
enum Weekday today = Monday;
```
- Modifiers:
  - C offers modifiers that can applied to basic data types. It changes their range and size.
    - `signed`: can store both positive and negative integers, IE: `signed int num = -5;`
    - `unsigned`: can store only positive values, IE: `unsigned int num = 15;`
    - `short`: reduces storage size, IE: `short int num = 50;`
    - `long`: increases the storage size, IE: `long int num = 100000;`
- Typedef:
  - Used to give a new name to an existing type
```c
typedef unsigned int uint;
uint x = 100;
```
- Size and range of basic data types:

| Data Type | Size (bytes) | Range (signed)                 | Range (unsigned)  | Note                                                       |
|-----------|--------------|--------------------------------|-------------------|------------------------------------------------------------|
| `char`    | 1            | -128 - 127                     | 0 - 255           | `Char` can be signed or unsigned depending on the compiler |
| `int`     | 4            | -2,147,483,648 - 2,147,483,647 | 0 - 4,294,967,295 | n/a                                                        |
| `float`   | 4            | 3.4E-38 - 3.4E+38              | n/a               | n/a                                                        |
| `double`  | 8            | 1.7E-308 - 1.7E+308            | n/a               | n/a                                                        |

---

# Controlling the Flow

Control flow is the orders that statements, instructions, or functions are executed or evaluated. There are several control flow options in C.

- Types of control flow:
  - `Conditional statements`: executes different code based on certain conditions.
  - `Loops`: repeat a block of code multiple times (or forever).
  - `Jump statements`: unconditional control transfer to another part of the program.

- Condition statements:
  - `if/else if/else` statement
    - This statement allows execution of a block of code `if` a specific condition is true. You may also use an `else if` to test multiple conditions to be true. Otherwise, the alternative block of code in the `else` is executed. Example:
```c
int x = 10;

if (x > 10) {
   printf("x is greater than 10");
} else if (x > 5) {
   printf("x is greater than 5 less than 10");
} else {
   printf("x is less than 5");
}
```
- Switch statements
  - Execute one block of code among multiple depending on the value of an expression. Switch statements have a `default` condition, this condition is executed if none of expressions match the case. Example:
```c
int day = 2;

switch (day) {
  case 1:
    printf("Monday");
  case 2:
    printf("Tuesday");
  case 3:
    printf("Wednesday);
  default:
    printf("That's not a f*ckin day...");
}
```
- Loops:
  - `for` loop repeats a block of code a known number of times, IE:
```c
for (int i = 0; i < 5; i++) {
  printf("%d", i);
}
```
  - `while` loop is used to repeat code while a condition is evaluated to true, IE:
```c
int i = 0;

while (i < 5) {
  printf("%d", i);
  i++;
}
```
  - `do-while` loop is similar to a while loop. However, the condition is checked AFTER the loop has already executed. This guarantees that the loop will run at least once, IE:
```c
int i = 0;

do {
  printf("%d", i);
  i++;
} while (i < 5);
```
- Jump statements:
  - `break`: used to exit a loop prematurely regardless of condition, IE:
```c
for (in i = 0; i < 5; i++) {
  if (i == 2) {
    break;
  }
  printf("%d", i);
}
```
  - `continue`: skip current iteration and move to next, IE:
```c
for (in i = 0; i < 5; i++) {
  if (i == 2) {
    continue;
  }
  printf("%d", i);
}
```
  - `goto`: allows you to jump to predefined labels within the program, IE:
```c
int i = 0;

// label
start:
  printf("%d", i);
  i++;
  if (i < 3) {
    goto start;
  }
```
##### NOTE: it is worth noting that `goto` is usually frowned upon because it can make the code harder to follow. However, do what you want. It's your code. It is also worth noting that `goto` is useful for deep nested loops.
- Return statements:
  - Used to exit a function and return a value from that function call, IE:
```c
int add(int a, int b) {
  return a + b;
}
```
- Summary of control flows cheat sheet:

| **Construct** | **Type**              | **Description**                                                                         | **Syntax**                                                                      |
|---------------|-----------------------|-----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| **if**        | Conditional Statement | Executes a block of code if the condition is true.                                      | `if (condition) { // code }`                                                    |
| **if-else**   | Conditional Statement | Executes one block of code if the condition is true, another if the condition is false. | `if (condition) { // code } else { // code }`                                   |
| **else-if**   | Conditional Statement | Tests multiple conditions sequentially.                                                 | `if (condition1) { // code } else if (condition2) { // code } else { // code }` |
| **switch**    | Conditional Statement | Selects one block of code to execute from multiple options based on a variable’s value. | `switch (variable) { case value1: // code; break; ... default: // code }`       |
| **for**       | Loop                  | Repeats a block of code a specific number of times.                                     | `for (initialization; condition; increment) { // code }`                        |
| **while**     | Loop                  | Repeats a block of code while a condition is true.                                      | `while (condition) { // code }`                                                 |
| **do-while**  | Loop                  | Executes a block of code at least once and repeats while the condition is true.         | `do { // code } while (condition);`                                             |
| **break**     | Jump Statement        | Exits from a loop or switch statement immediately.                                      | `break;`                                                                        |
| **continue**  | Jump Statement        | Skips the current iteration of a loop and continues with the next iteration.            | `continue;`                                                                     |
| **goto**      | Jump Statement        | Transfers control to a labeled part of the code. **Use is discouraged.**                | `goto label; ... label: // code`                                                |
| **return**    | Function Control      | Exits a function and optionally returns a value to the calling function.                | `return value;`                                                                 |

---

# C Functions

A function in C is a block of code that can be called multiple times throughout the program. Functions are usually designed to do one thing and do it well. This allows for easily readable code that provides better maintainability. It allows you to write a chunk of code one time and use it over and over again.

When declaring a function in C you use a `prototype`. You must declare a function _before_ use. This is typically done before the `main` function of the program. The declaration informs the compiler about the name, return type, and parameters of the function.

The syntax of a function is: `return type function_name(parameters)`. As an example of a basic function:
```c
// create a function prototype
int add(int a, int b);
```

Function definitions specify the actual code that is executed within the function when it is called. This is a set of instructions that make up the functions logical body:
```c
int add(int a, int b) {
  return a + b;
}
```

Once the function has been declared and defined you can call the function by simply calling its name and passing the required arguments. For example:
```c
int result = add(1, 2);
// this returns 3
```

It is entirely possible to create a function that returns nothing. In order to do so you will provide it with the `void` return type:
```c
void logWelcome() {
  printf("Hey nerd!");
}
```

Recursion is when a function calls itself. This can be useful for solving problems without having to write extra code. For example:
```c 
int factorial(int n) {
  if (n == 0) {
    return 1;
  } else {
    return n * factorial(n-1);
  }
}
```
Notice how we recall the function from within itself. 

Key concept cheat sheet of functions:

| **Element**              | **Description**                                                                                   |
|--------------------------|---------------------------------------------------------------------------------------------------|
| **Function Declaration** | Specifies the function's name, return type, and parameters.                                       |
| **Function Definition**  | Contains the code (body) that performs the function's task.                                       |
| **Function Call**        | Invokes the function, passing the necessary arguments to the function.                            |
| **Return Type**          | Indicates the type of value the function returns (IE: `int`, `float`, `void` if no return value). |
| **Parameters**           | Inputs to the function, passed when calling the function.                                         |
| **Void Function**        | A function that performs an action but does not return any value.                                 |
| **Recursion**            | A function that calls itself for repetitive tasks.                                                |

---

# What the F*ck is a pointer?!

A pointer is a variable that stores the memory address of another variable. Instead of holding the value of the variable it "points to" the memory address where the value is stored. This provides a powerful way to efficiently use memory manipulation and is an essential for things like dynamic memory allocation, arrays, and function calls. 

#### Declaring a pointer

To declare a pointer you specify the data type of the variable followed by an asterisk (`*`) and finally the pointer name.
```c
// data_type *pointer_name;
int *a;
```
- The `*a` indicates that the variable `a` is a pointer to an integer.
- Initially the pointer will contain an arbitrary memory address and should be assigned a valid address before use.

#### Initialize a pointer

To initialize a pointer you assign them the address of another variable using the _address of operator_ (`&`).
```c
// pointer_name = &variable;
int x = 12;
int *p = &x; // this now holds the address of the `x` variable
```
- The `x` variable stores the integer `12`
- The `p` stores the memory address of the `x` variable, but not the value of it.

#### Dereference a pointer

Dereferencing pointers is when you access the value stored at the memory address.
```c
// *pointer_name;
int x = 12;
int *p = &x;
printf("%d", *p); // Dereferencing: prints the value of `x` which is 12.
```

#### Null pointers

Null pointers are a pointer that points to nothing or an invalid memory location. When you initialize a pointer, and it doesn't point to anything it is good practice to initialize it to null.
```c
int *p = NULL;
```
- This indicates that the pointer is not pointing to anything valid yet.

#### Arrays

An array acts as pointers to the first element in the array. You can use pointers to iterate through the array. This way you don't have to declare the pointer (`&`) for an array since it's already technically a pointer.
```c
int arr[] = {10, 20, 30};
int *p = arr;
printf("%d", *p);  // output is 10
p++;
printf("%d", *p);  // output is 20
```

#### Pointer arithmetic

Pointer arithmetic is when you navigate through memory locations that are contiguous (such as arrays) using a pointer.

You can increment and decrement a pointer in order to move to the next value.
```c
int arr[] = {1, 2 ,3};
int *arrP = arr; // this pointer points to the first element of the array
arrP++;          // this pointer now points to the second value of the array
```

You can also add or subtract an integer to move the pointer by that many elements.
```c
arrP = arrP + 2; // move by 2 elements
```

Using pointers with functions can allow you to modify a variable or array directly without returning a value. 
```c
void incPointer(int *p) {
  (*p)++;  // increment the value of the pointer
}

int main() {
  int x = 5;
  incPointer(&x);  // pass memory address of x variable
  printf("%d", x); // should output 6
  return 0;
}
```

#### Pointerception

C allows you to point to pointers it's like pointerception but less cool and more confusing.
```c
// data_type **pointer_name
int x = 10;         // create an integer variable with value 10
int *p = &x;        // create a pointer to that variable
int **pp = &p;      // do pointerception and confuse the f*ck out of everyone

printf("%d", **pp); // outputs the value of `x` (10)
```

#### Downsides and upsides of pointers

There are of course downsides and upsides of pointers. We will start with the downsides:

- Pointers can become extremely complex and confusing. They can make your code extremely hard to read, understand, and debug.
- Incorrect use of pointers can lead to memory leaks, segmentation faults, and security vulnerabilities.

Now the upsides of pointers:

- Pointers are very efficient at managing memory and allow dynamic memory allocation. 
- They provide direct memory access that allows you to manipulate data at very low levels.

#### Pointer cheat sheet

Key concepts to remember (cheat sheet):

| **Pointer Concept**        | **Description**                                                                  | **Example**               |
|----------------------------|----------------------------------------------------------------------------------|---------------------------|
| **Pointer Declaration**    | Declares a pointer to store the address of a variable.                           | `int *p;`                 |
| **Pointer Initialization** | Initializes a pointer by assigning the address of a variable.                    | `p = &x;`                 |
| **Dereferencing**          | Accesses the value stored at the memory address a pointer points to.             | `*p`                      |
| **Null Pointer**           | A pointer that points to nothing.                                                | `int *p = NULL;`          |
| **Pointer Arithmetic**     | Performing arithmetic operations on pointers (incrementing, decrementing, etc.). | `p++;`                    |
| **Pointer to Array**       | Points to the first element of an array, allowing easy array traversal.          | `int *p = arr;`           |
| **Pointer to Function**    | Passes pointers to functions, allowing them to modify variables or arrays.       | `void increment(int *p);` |
| **Pointer to Pointer**     | A pointer that points to another pointer.                                        | `int **pp = &p;`          |

#### How not to use a pointer

As a bonus as mentioned earlier pointers can get extremely complex. So, we will be showing you an example of a complex pointer and why you need to be careful when creating pointers and using them in your code. The code below should never be used in production, and never be used in anything. Read the comments to understand exactly what is going on:
```c
int main() {
  // declare an integer and set it to 42
  int x = 42;
  
  // create a pointer to that integer
  int *p = &x;
  
  // create a pointer to that pointer
  int **pp = &p;
  
  // create a pointer to that pointer to that pointer
  int ***ppp = &pp;
  
  // create a pointer to that pointer to that pointer to that pointer
  int ****pppp = &ppp;
  
  // WTF AM I DOING
  // pointer arithmetic combined with dereferencing
  int *****ppppp = &pppp;
  
  // WHY DOES THIS WORK?!
  // modify x through absurd dereferencing and pointer arithmetic
  *****ppppp[0][0][0][0][0] = 99;
  
  // should print 99
  printf("x = %d\n", x);    
  
  // same as above but WTF
  printf("x (via ppppp): %d\n", *****ppppp[0][0][0][0][0]);
  
  // get the addresses
  printf("Address of p: %p\n", *****ppppp[0][0][0][0]);
  printf("Address of pp: %p\n", *****ppppp[0][0][0]);
  printf("Address of ppp: %p\n", *****ppppp[0][0]);
  printf("Address of pppp: %p\n", *****ppppp[0]);
  return 0;
}
```

# Memory Allocation

Memory allocation is the process of allocating and managing memory during the execution of a program. There are two main types of memory allocations in C:
- `Static Memory Allocation`: this memory is allocated at compilation time.
- `Dynamic Memory Allocation`: this memory is allocated dynamically at runtime using pointers.

There are several functions to perform memory management. They are:
- `malloc()`: allocates memory dynamically
  - Benefits:
    - Allows dynamic memory allocation making it possible to only allocate the memory you need.
    - Allows flexibility by providing the ability to allocate memory of any size.
    - Does not have any initialization overhead.
  - Issues:
    - The memory is not initialized and contains garbage values. This may lead to undefined behavior if the memory is accessed before initialized.
    - Provides a risk of memory leaks if you don't `free()` the memory allocation. 
    - Even though it's faster than `calloc()` you have to manually initialize it which adds additional complexity.
- `calloc()`: allocates memory an array and initializes to zero.
  - Benefits:
    - Initializes all memory to zero.
    - Is designed for arrays which makes it easier to understand.
  - Issues:
    - Performance overhead because it is initialized to zero.
    - More complicated to use because it requires two arguments.
    - Can produce over allocation which can produce memory waste or crashes.
- `realloc()`: resizes previously allocated memory.
  - Benefits:
    - Allows you to resize memory allocation dynamically as long as that memory is already allocated.
    - Will preserver existing data on resize.
  - Issues:
    - Does not expand the current block, just relocates the existing block somewhere else.
    - Has the potential for data loss. If it fails it will return `NULL`.
    - Has performance overhead because it has to move the memory to another location.
- `free()`: frees dynamically allocated memory.
  - Benefits:
    - Can help prevent memory leaks.
    - Is a necessity for memory management in C.
  - Issues:
    - If you free memory and continue to use a pointer without resetting it to `NULL`, it will become a dangling pointer. Dereferencing these pointers can lead to unexpected behavior.
    - If you call free on the same pointer more than once this may result in a `double free` which may lead to undefined behavior, crashes, and/or vulnerabilities.
    - If you forget to free dynamically allocated memory this will result in memory leaks.

#### Static memory allocation

When you allocate memory statically you determine the lifetime and size of the variables at compilation time. These variables memory is allocated and deallocated automatically when the program starts and ends. Variables declared outside of functions or when using the `static` keyword fall into the category. Arrays with a fixed size also fall into this category. An example of a static memory allocation is as follows:
```c
// allocate the size of the array statically
int arr[10];
```

#### Dynamic memory allocation

When you allocate memory dynamically you are doing so with pointers at runtime. This allows more flexible memory allocation because you can allocate memory based on the needs of the program. An example of dynamic memory allocation:
```c
// dynamically allocate the memory at runtime. This will contain garbage values
int *ptr = (int*) malloc(5 * sizeof(int)); 
```
You can use `calloc` to allocate the memory for an array:
```c
// allocates memory for an array of 5 integers and initializes them to 0
int *ptr = (int*) calloc(5, sizeof(int));
```
You can also use `realloc` to change the size of an already allocated memory section:
```c
// allocates memory for 5 integers
int *ptr = (int*) malloc(5 * sizeof(int));

// reallocates memory to store 10 integers
ptr = (int*) realloc(ptr, 10 * sizeof(int)); 
```

You always have to use `free` after you have allocated memory and are done with it:
```c
free(ptr);
ptr = NULL;
```

#### Memory segments
C memory is divided into multiple segments where you can allocate memory.
- Stack:
  - Local variables and functions.
  - Automatically allocated and deallocated.
  - Limited, too much memory used leads to stack overflows
- Heap:
  - Dynamically allocated memory comes from here (`malloc`, `calloc`, `realloc`).
  - Heap memory is managed manually
  - No automatic reallocation can lead to memory leaks if `free()` isn't used.
- Global/Static memory:
  - Variables declared outside of any function and variables using the `static` keyword
  - Memory is allocated at compile time


#### Possible issues with memory

- Memory leaks
  - A memory leak is when dynamically allocated memory is not freed after it is no longer needed.
```c
// if we do not free the `ptr` variable this will cause a memory leak.
int* ptr = (int*) malloc(10 * sizeof(int));
```
- Dangling pointers
  - A dangling pointer is when a declared pointer points to memory that has already been freed.
```c
// create a pointer
int *ptr = (int*) malloc(sizeof(int));

// free the pointer
free(ptr);

// reference the already freed pointer
// this is dangerous and will lead to undefined behavior
*ptr = 5;
```
- Double free
  - A double free is when `free()` is used more than once on the same pointer
```c
// create a pointer
int *ptr = (int*) malloc(sizeof(int));

// free the pointer
free(ptr);

// free it again
// this will cause undefined behavior, or crashes
free(ptr);
```
- Wild pointers
  - A wild pointer is an uninitialized pointer. This means if you use a pointer before it has been assigned valid memory.
```c
// create a uninitialized pointer
// notice how we don't give it any memory
int *ptr;

// dereference the pointer
// this will lead to undefined behavior
*ptr = 10;
```

#### Memory allocation cheatsheet

| **Function** | **Purpose**                                            | **Initialization**            | **Usage Example**                           |
|--------------|--------------------------------------------------------|-------------------------------|---------------------------------------------|
| `malloc()`   | Allocates memory dynamically.                          | No (contains garbage values). | `int *p = (int*) malloc(10 * sizeof(int));` |
| `calloc()`   | Allocates memory for an array and initializes to zero. | Yes (initialized to 0).       | `int *p = (int*) calloc(10, sizeof(int));`  |
| `realloc()`  | Resizes previously allocated memory.                   | Preserves existing data.      | `p = (int*) realloc(p, 20 * sizeof(int));`  |
| `free()`     | Frees dynamically allocated memory.                    | N/A                           | `free(p);`                                  |

# Directives and Macros

C provides preprocessed directives and macros that are processed before compilation begins. These allow developers to include files, define constants, and create conditional compiled code. This improves code organization, readability, and efficiency.

#### Preprocessor directives

These are lines in the code that start with `#`. They are instructions to the preprocessor that run before the compiler. Common types include:
- `#include`
  - Include a source file or header file. Header files are either standard C library or a user defined file.
```c
// SYNTAX: #include <header_file>

#include <stdio.h>   // system files use <file.h>

#include "myfile.h"  // user defined uses "file.h"
```
- `#define`
  - Define a macro or constant. 
```c
// defining a constant
// SYNTAX: #define CONSTANT_NAME value
#define PI 3.14159
#define MAX_SIZE 100

// defining a macro
// SYNTAX: #define MACRO_NAME(params) expression
#define SQR(x) ((x) * (x))

// define a multi line macro
#define MULTI_MACRO(x)          \
  do {                          \
    printf("Value: %d", x);     \
    if (x > 2) {                \
      printf("Greater than 2"); \
    } else {                    \
      printf("Less than 2");    \
    }                           \
  } while (0)
```
- `#undef`
  - Undefine a macro. This macro must have already been defined using `#define`.
```c
// SYNTAX: #undef MACRO_NAME

// define the macro
#define PI 3.14159

// now undefine the above defined macro
#undef PI
```
- `ifdef`/`ifndef`
  - Conditional compilation based on whether a macro is defined or not. These are useful for platform specific code/debugging.
```c
// if the macro IS defined 
#ifdef MACRO_NAME
  // perform whatever you need to do ONLY if the macro IS defined
#endif

// if the macro IS NOT defined
#ifndef
  // perform whatever you need to do ONLY if the macro IS NOT defined
#endif
```
- `#if`/`#elif`/`#else`/`#endif`
  - Conditional compilation based on conditions. Allows more control over `#define`. Works like an `if/else` statement
```c
#if CONDITION
  // perform action
#elif OTHER_CONDITION
  // perform other action
#else
  // perform another action
#endif
```
- `#pragma`
  - Special compiler instructions. Behavior varies depending on compilers, is used mostly for optimization, warnings, or other compiler specific features.
```c
// SYNTAX: #pragma some_instruction

// define a pragma to disable a warning
#pragma warning(disable:4996)
```

#### Common issues with macros

Some common issues encountered with macros are:
- Lack of type safety:
```c
#define SQR(x) (x * x)

// this will expand to 3+1 * 3+1 which is not what we are looking for
printf("%d", SQR(3+1));
```
- Unexpected side effects:
```c
#define DOUBLE(x) (x + x)
int a = 5;

// this expands to a++ + a++ which modifies the variable twice
printf("%d", DOUBLE(a++));
```
- Debugging difficulty:
  - Since macros are replaced before compilation debugging issues related to macros can become extremely challenging.

#### Directives and macros cheat sheet

| **Directive/Macro**                  | **Description**                                                         |
|--------------------------------------|-------------------------------------------------------------------------|
| `#include`                           | Includes external files (header files).                                 |
| `#define`                            | Defines macros or constants.                                            |
| `#undef`                             | Undefines a previously defined macro.                                   |
| `#ifdef` / `#ifndef`                 | Conditional inclusion based on whether a macro is defined.              |
| `#if` / `#elif` / `#else` / `#endif` | Conditional compilation based on specific conditions.                   |
| `#pragma`                            | Provides special instructions to the compiler (compiler-specific).      |
| **Macros**                           | Preprocessor instructions that replace text or expressions in the code. |

---

# Debugging and Errors Handling

Debugging and error handling are crucial for all developers not just C developers. However, since there are no high-level features things like exceptions developers need to be able to handle errors manually and make effective use of debugging tools/strategies.

#### Debugging in C

Debugging is the process of identifying and fixing bugs/errors in a program. There are a lot of debugging tools, and you should use what you want. We will not be going into all of them in this course but will be focusing on the basic examples. Some common techniques include:

- Print statements
  - This is by far the simplest method, you put print statements where you think the bug is and see what data is being passed to it. This allows you to print potential problem values and variables.
- GDB debugger
  - The GNU debugger is a powerful tool that allows you to inspect your C code execution, set breakpoints, step through the code, examine variable values, and track the cause of runtime errors
- Compiler warnings and errors
  - Modern C compilers provide warnings that may catch potential issues at compile time. Such as unused variables, incorrect types, possible zero division, etc. You should always enable compiler warnings when compiling your program.
- Static analysis tools
  - Tools like `lint` analyze source code for possible errors, suspicious constructs, and coding standard violations. These tools are useful for detecting before compiling.

#### Error handling

Error handling is done manually in C. It is done by checking return values of functions using error codes and handling the cases of the codes. C lacks built in error handling like try/catch blocks.

- Checking return values:
  - Many standard libraries return special values when they fail such as: `NULL`, `-1`, or `EOF`.
```c
#include <stdio.h>

int main() {
  // open a file and assign it to a pointer named `fh`
  FILE *fh = fopen("filename.txt", "r");
  
  // check if the pointer is null or not
  if (fh == NULL) {
    // print an error
    perror("FAILED TO OPEN FILE");
    
    // return 1 to indicate it failed to open
    return 1;
  }
  
  // close the file
  fclose(fh);
  
  // return 0 to indicate success
  return 0;
```
- Using `errno` for error reporting
  - `errno` is a global variable in C. It stores the error code when certain standard library functions fail. This may provide more detailed information.

```cpp
#include <stdio.h>
#include <errno.h>
#include <string.h>

int main() {
  // open a file and assign it to the `fh` pointer
  FILE *fh = fopen("filename.txt", "r");
  
  // check if the pointer is null or not
  if (fh === NULL) {
    
    // if the pointer is null return the errno info in a string
    printf("hit error opening file: %s\n", strerror(errno));
    
    // return 1 to indicate that it failed
    return 1;
  }
  
  // close the file
  fclose(fh);
  
  // return 0 to indicate success
  return 0;
```

#### Error handling cheat sheet

| **Aspect**                   | **Description**                                                                  |
|------------------------------|----------------------------------------------------------------------------------|
| **Print Statements**         | Simple debugging method by printing variable values and program state.           |
| **GDB (Debugger)**           | Allows stepping through code, setting breakpoints, and inspecting program state. |
| **Compiler Warnings**        | Enable warnings to catch potential issues at compile-time (`-Wall`).             |
| **Static Analysis Tools**    | Tools like `lint` help detect bugs and improve code quality.                     |
| **Return Value Checking**    | Manually check function return values to detect errors (e.g., `fopen()`).        |
| **`errno` and `strerror()`** | Provides detailed error reporting for certain standard library functions.        |

---

# Write some Code!

Now that we've been through all you will need to know to start writing in C code lets go ahead and write a program together. The objective of this program will be to do the following:

- Dynamically allocate memory for an array of integers
- Fill the array with user input
- Calculate the sum of the array elements
- Handle possible errors
- Use macros to make the code cleaner
- Use print statements for debugging
- Use simple logging for error capturing

#### The code


```cpp
#include <stdio.h>
#include <stdlib.h>
#include <errno.h>
#include <string.h>
// these header files are standard C library
// stdio: includes things like printf and scanf
// stdlib: includes things like malloc and free
// errno: includes error codes for functions like fopen
// string: includes things like strerror for human readable error messages

// define a constant using a macro
#define MAX_ARRAY_SIZE 100

// define a macro to get the square of a number
#define SQR(x) ((x) * (x))

// create function prototypes
// these tell the compiler that the functions will be defined later
int allocateArray(int **arr, int size);
int calculateSum(int *arr, int size);
void logError(const char *message);


// main function
int main() {
  
  // initialize the pointer for the array
  int *arr = NULL;
  int size;
  
  // step #1: get the array size from the user
  printf("Enter the size of the array (max size: %d): ", MAX_ARRAY_SIZE);
  scanf("%d", &size);
  
  // handle any errors that might arise while doing so by checking if the size is within limits
  if (size < 0 || size > MAX_ARRAY_SIZE) {
    logError("Invalid array size");
    printf("Error: Invalid array size\n");
    return 1;
  }
  
  // step #2: allocate the memory of the array automatically using the allocateArray function
  if (allocateArray(&arr, size) != 0) {
    // exit on failure
    printf("Memory allocation failed\n");
    return 1;
  }
  
  // step #3: fill the array with values from the user
  printf("Enter %d integer values:\n", size);
  for (int i = 0; i < size; i++) {
    scanf("%d", &arr[i]);
  }
  
  // step #4: print the numbers that the user entered for debugging
  printf("You entered: ");
  for (int i = 0; i < size; i++) {
    printf("%d ", arr[i]);
  }
  // add a new line after we have printed the entered numbers out
  printf("\n");
  
  // step #5: calculate the sum of the array element
  int sum = calculateSum(arr, size);
  printf("The sum of the array of elements is: %d\n", sum);
  
  // step #6 demonstrate the SQR macro
  int number = 5;
  printf("The square of %d is: %d\n", number, SQR(number));
  
  // step $7: free the allocated memory to avoid leaks
  free(arr);
  printf("Memory freed successfully!\n");
  
  // return a success
  return 0;
}

// this function will allocate the memory for the array
int allocateArray(int **arr, int size) {
  
  /* 
  create a pointer for the array
  it is worth noting that you do not actually need to 
  cast malloc here since it will be a *void now
  however due to the content and the target audience of
  this course we will be casting it here
  
  TL;DR: ima cast malloc and you can't stop me
  */
  *arr = (int*) malloc(size * sizeof(int));
  if (*arr == NULL) {
  
    // log the error
    logError("Memory allocation failed!");
    
    // return error code on failure
    return -1;
  }
  
  // return success
  return 0;
}

// this function calculates the sum of the array elements
int calculateSum(int *arr, int size) {
  // create a variable for the sum
  int sum = 0;
  
  // run through the elements and add them to sum
  for (int i = 0; i < size; i++) {
    sum += arr[i];
  }
  
  // return the sum
  return sum;
}

// this function will log all errors to a file for debugging
void logError(const char *message) {

  // initialize the pointer for the file
  FILE *log = fopen("error.log", "a");
  
  // make sure the pointer is initialized successfully
  if (log != NULL) {
  
    // log the error if it is
    fprintf(log, "Error: %s\n", message);
    
    // close the file
    fclose(log);
  }
}
```

#### Compiling the file

Now you will need to save and compile this file like so:
```bash
salty@Loki:/tmp$ gcc -o test -Wall test.c 
salty@Loki:/tmp$ ./test
Enter the size of the array (max size: 100): 8
Enter 8 integer values:
1
2
3
4
5
6
7
8
You entered: 1 2 3 4 5 6 7 8
The sum of the array of elements is: 36
The square of 5 is: 25
Memory freed successfully!
salty@Loki:/tmp$
```

What did we just do? Well, we used the gcc compiler in order to compile the C file into an executable that we can call after compilation is finished. We used the `-Wall` to show all warnings that seen during compilation.

---

#### Sponsor

Special thanks to the sponsor of this course! Skip2 Networks!

<p align="center">
    <img src="../.github/sponsor_images/s2.svg">
</p>

Web Acceleration Platform: DNS, CDN, and WAF solutions for the modern web. Building faster internet infrastructure for scale.

---


# That's all!

Now you have finished the course! We hope you got enough out of this to start writing in C and be confident in what you're doing. We have taught you the bare basics of C and how it works. This course is designed to provide beginners the information they need in order to start writing C code. Please keep in mind:

#### Support the Bible

Once again, this course is offered for free by The Perkins Cybersecurity Educational Fund in collaboration with Malcore! If you found this information valuable and want to support the continued development of the Malware Bible please consider:
- Donating to the Malware Bible Fund → [Donate Here](https://donorbox.org/malware-bible-fund)
- Registering for Malcore → [Sign Up](https://m4lc.io/courses/register)
- Joining the Malcore Discord → [Join Today](https://m4lc.io/courses/discord) 

#### Become a sponsor

These courses reach thousands of cybersecurity professionals, researchers, students, and teachers worldwide who actively engage in learning and advancing the field. Sponsoring our educational initiative not only supports free cybersecurity education but also places your brand in front of a highly technical and security-conscious audience.

Interested in partnering? Let's talk about how your organization can be featured in our future courses: [Contact us today!](https://perkinsfund.org/) Please view our [Sponsorship Packages](../.github/sponsorships/sponsorship_package.md) for more details!
