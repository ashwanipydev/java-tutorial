### Why we use packages?
- When we want to use any predefined classes in our program then we need to import appropriate package in our program.

### What is packages in java?
- Nothing but collection of predefined classes and Interface .

### Why we use java.lang package?
- In java java.lang package is default package.
- It is very important package among all other packages.
- String, System, class in present insdie the java.lang package...

### Which is the most important package in java?
 The `java.lang` package in Java is one of the core packages and contains fundamental classes that are automatically imported into every Java program. Some of the important classes in the `java.lang` package include:

1. `Object`: The root class for all Java classes.
2. `String`: Represents a sequence of characters.
3. `Integer`, `Long`, `Float`, `Double`, `Byte`, `Short`: Wrapper classes for primitive data types.
4. `Boolean`: Wrapper class for boolean primitive data type.
5. `Character`: Wrapper class for char primitive data type.
6. `Throwable`: The superclass of all errors and exceptions in the Java language.
7. `Exception`: The superclass for all checked exceptions.
8. `RuntimeException`: The superclass for all unchecked exceptions.
9. `Thread`: Represents a thread of execution.
10. `System`: Provides access to system properties and system-level resources.

These are some of the most commonly used classes in the `java.lang` package, but there are more classes and interfaces available. This package contains fundamental classes and interfaces that are essential for basic Java programming.

# Java Programming Structure

```java
import java.lang.*; // default package not required to mansion  in our Java programm
class Test
{
    public static void main(String[] args)
    {
        System.out.println("Testing");
    }
}
```
<div style="text-align:center">

![](https://media.geeksforgeeks.org/wp-content/uploads/20200823163148/machinecode-300x162.png)

![](https://media.geeksforgeeks.org/wp-content/uploads/20230520121734/How-Java-is-Platform-Independent-768.png)

</div>


In Java, there are several ways to print messages to the console or other output streams. Some of the common methods include:

1. **Using System.out.println()**: This is perhaps the most basic and widely used method to print messages to the console. It prints the specified message followed by a newline character.

   ```java
   System.out.println("Hello, world!");
   ```

2. **Using System.out.print()**: Similar to `println()`, but it doesn't append a newline character, so subsequent output will be on the same line.

   ```java
   System.out.print("Hello, ");
   System.out.print("world!");
   ```

3. **Using System.out.printf()**: This method allows you to format the output using format specifiers. It's similar to the `printf()` function in C.

   ```java
   int num = 10;
   System.out.printf("The value of num is %d%n", num);
   ```

<div style="text-align:center">

## Data Types in java

</div>


![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191105111644/Data-types-in-Java.jpg)




| Data Type    | Description                          | Size (in bytes) | Default Value      | Range                                       | Example Literals                  |
|--------------|--------------------------------------|-----------------|--------------------|---------------------------------------------|-----------------------------------|
| `byte`       | 8-bit signed integer                 | 1               | 0                  | -128 to 127                                 | `byte b = 10;`                    |
| `short`      | 16-bit signed integer                | 2               | 0                  | -32,768 to 32,767                           | `short s = 1000;`                 |
| `int`        | 32-bit signed integer                | 4               | 0                  | -2,147,483,648 to 2,147,483,647             | `int i = 1000000;`                |
| `long`       | 64-bit signed integer                | 8               | 0L                 | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 | `long l = 1000000000L;`      |
| `float`      | 32-bit floating point                | 4               | 0.0f               | ±1.40129846432481707e-45F to ±3.40282346638528860e+38F  | `float f = 3.14f;`                |
| `double`     | 64-bit floating point                | 8               | 0.0d               | ±4.94065645841246544e-324 to ±1.79769313486231570e+308 | `double d = 3.14;`                |
| `char`       | 16-bit Unicode character             | 2               | '\u0000'           | '\u0000' to '\uffff' (0 to 65,535)         | `char c = 'A';`                   |
| `boolean`    | Represents true or false             | 1               | false              | true or false                               | `boolean flag = true;`            |

These literals represent sample values assigned to variables of each data type.

---
## Why do we use data types in programming languages?
Data types in programming languages serve several important purposes:

1. **Memory Allocation**: Data types help allocate memory for variables. Different data types require different amounts of memory. For example, an integer may require 4 bytes of memory, while a floating-point number may require 8 bytes.

2. **Data Validation**: Data types enforce rules about what kinds of values variables can hold. This helps ensure that the program operates correctly and efficiently. For example, if a variable is declared as an integer, it cannot hold non-integer values like text or floating-point numbers.

3. **Optimization**: By specifying the data type of variables, the compiler can optimize the program's memory usage and performance. For example, knowing the data type of a variable allows the compiler to allocate exactly the right amount of memory and generate efficient machine code to manipulate that data.

4. **Type Safety**: Data types contribute to the type safety of a programming language. Type safety prevents certain kinds of errors, such as attempting to perform operations on incompatible types or accessing memory locations that do not contain valid data.

5. **Documentation**: Data types provide documentation to other programmers about the intended use of variables and functions. By specifying data types clearly, programmers can understand the purpose of variables and functions more easily.

Overall, data types play a crucial role in programming languages by enabling efficient memory management, enforcing rules about data manipulation, and enhancing the readability and maintainability of code.


### Where do we use data types in our programming?

1.  At the time of variable declarations.
2.  At the time of method creation.



