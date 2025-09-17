# 1.1  Printing and Comments

## Printing

Through our first program, we were exposed to a command that outputs information to the screen:

`System.out.println("Hello");`

It's a simple command, but there is a lot happening.  Here is a breakdown of the command:
* `System.out` - a java library containing tools for outputting
* `println()` - a command to specifically output the contents followed by a carriage return 
* `"Hello"` - the value to be outputted,  known as a string.  String values are enclosed within " "
* `;`  - statements end with a semicolon

### You Try
```
System.out.println("Hi");
System.out.println("There!!");
```

### Printing without a new line
Try this:
```
System.out.print("Hi");
System.out.print("There!!");
```
Similar to `println()`, `print()` outputs to the screen, however, there is no newline placed after the what is outputted.

### Concatenation (Joining Text Together)
In Java, we can combine strings together using the `+` operator. This is known as **concatenation**. It's useful when you want to build up output from multiple pieces of text or variables:

```
System.out.println("Hello " + "World!");
```

This will output:

```
Hello World!
```

We can also concatenate text with variable values:

```
String name = "Mr. Cheng";
System.out.println("Hello, " + name);
```

This will output:

```
Hello, Mr. Cheng
```

## Comments
In our programs, we often have content that we want the compiler to ignore and not translate.  Some reasons are:

* descriptions of the overall program
* multi-line descriptions of parts of the code
* single line descriptions of commands
* ignoring code for troubleshooting

### Single Line Comments //
In Java, we can ignore single lines of code by putting a // infront of it.

### Multiline Comments /*     */
If we want to have comment span multiple lines, we use /*  */
```
// Draw a box
System.out.println("*************");
System.out.println("*           *");
System.out.println("*           *");
System.out.println("*           *");
System.out.println("*************");
      
// Draw another box
/*
System.out.println("*************");
System.out.println("*           *");
System.out.println("*           *");
System.out.println("*           *");
System.out.println("*************");
*/
```

