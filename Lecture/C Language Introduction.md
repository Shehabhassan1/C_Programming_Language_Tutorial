
C is a procedural programming language initially developed by Dennis Ritchie in the year 1972 at Bell Laboratories of AT&T Labs. It was mainly developed as a system programming language to write the UNIX operating system.
  ![[images.jpeg]]                  

The main features of the C language include:

- General Purpose and Portable
- Low-level Memory Access
- Fast Speed
- Clean Syntax
## Why Should We Learn C?

Many later languages have borrowed syntax/features directly or indirectly from the C language. Like syntax of Java, PHP, JavaScript, and many other languages are mainly based on the C language. C++ is nearly a super set of C language (Only a few programs may compile in C, but not in C++).

So,  if a person learns C programming first, it will help him to learn any modern programming language as well. As learning C help to understand a lot of the underlying architecture of the operating system. Like pointers, working with memory locations, etc.


## Difference Between C and C++

C++ was created to add the OOPs concept into C language so they both have very similar syntax but both are a bit different from each other. Following are some main differences between C and C++ Programming language.

- C++ supports OOPs paradigm while C only have procedural concept of programming.
- C++ have exception handling capablities. In C, we have to resolve manually.
- There are no references in C.

## Beginning with C Programming

### ****Writing the First Program in C****

The following code is one of the simplest C programs that will help us the basic syntax structure of a C program.

#include <stdio.h>

int main() {
  int a = 10;
  printf("%d", a);
  return 0;  
}

## Components of a C Program:

### ****1. Header Files Inclusion – Line 1 [#include <stdio.h>]****

The first and foremost component is the inclusion of the Header files in a C program. A header file is a file with extension .h which contains C function declarations and macro definitions to be shared between several source files. All lines that start with ****#**** are processed by a preprocessor which is a program invoked by the compiler. In the above example, the preprocessor copies the preprocessed code of stdio.h to our file. The .h files are called header files in C.  
Some of the C Header files:

- stddef.h – Defines several useful types and macros.
- stdint.h – Defines exact width integer types.
- stdio.h – Defines core input and output functions
- stdlib.h – Defines numeric conversion functions, pseudo-random number generator, and memory allocation
- string.h – Defines string handling functions
- math.h – Defines common mathematical functions.

### ****2. Main Method Declaration – Line 2 [int main()]****

The next part of a C program is to declare the main() function. It is the entry point of a C program and the execution typically begins with the first line of the main(). The empty brackets indicate that the main doesn’t take any parameter (See [this](https://www.geeksforgeeks.org/difference-int-main-int-mainvoid/) for more details). The int that was written before the main indicates the return type of main(). The value returned by the main indicates the status of program termination. See [this](https://www.geeksforgeeks.org/fine-write-void-main-cc/) post for more details on the return type.

### ****3. Body of Main Method – Line 3 to Line 6 [enclosed in {}]****

The body of a function in the C program refers to statements that are a part of that function. It can be anything like manipulations, searching, sorting, printing, etc. A pair of curly brackets define the body of a function. All functions must start and end with curly brackets.

### ****4. Statement – Line 4 [printf(“Hello World”);]****

Statements are the instructions given to the compiler. In C, a statement is always terminated by a ****semicolon (;).**** In this particular case, we use printf() function to instruct the compiler to display “Hello World” text on the screen.

### ****5. Return Statement – Line 5 [return 0;]****

The last part of any C function is the return statement. The return statement refers to the return values from a function. This return statement and return value depend upon the return type of the function. The return statement in our program returns the value from main(). The returned value may be used by an operating system to know the termination status of your program. The value 0 typically means successful termination. 

## ****How to Execute the Above Program?****
https://www.freecodecamp.org/news/how-to-install-c-and-cpp-compiler-on-windows/
https://www.mingw-w64.org/
In order to execute the above program, we need to first compile it using a compiler and then we can run the generated executable. There are online IDEs available for free like [GeeksforGeeksIDE](https://ide.geeksforgeeks.org/), that can be used to start development in C without installing a compiler.

1. _****Windows:****_ There are many free IDEs available for developing programs in C. 
2. _****Linux:****_ GCC compiler comes bundled with Linux which compiles C programs. 
3. _****macOS:****_ macOS already has a built-in text editor where you can just simply.

## Application of C 

- Operating systems: such as Unix, Linux, and Windows.
- Embedded systems: C such as microcontrollers, microprocessors, and other electronic devices.
- System software: C such as device drivers, compilers, and assemblers.
- Networking: C such as web servers, network protocols, and network drivers.