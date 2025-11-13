# Ex.No: 1(A) — Introduction to Java Programming, Data Types, Variables and Operators
## Question

Lovely has just started learning Java and wants to understand how different print statements work in Java.
Write a program that:
Reads her name, age, and favorite decimal number
Prints her greeting using System.out.print()
Prints her age using System.out.println()
Prints her favorite number using System.out.printf() with 2 decimal places

### Input Format

First line: String → Lovely's name
Second line: int → age
Third line: float → favorite decimal number

### Output Format

Greeting using print()
Age using println()
Favorite number using printf()

## Aim

To write a Java program using variables and different output statements (print, println, printf) to display user input in various formats.

## Algorithm

• Start the program.

• Create a Scanner object to read input.

• Read the name as a string.

• Read the age as an integer.

• Read the favorite decimal number as a float.

• Use System.out.print() to display the greeting.

• Use System.out.println() to display the age.

• Use System.out.printf() to display the favorite number with two decimal places.

• End the program.

## Program
```
Program to implement variables and Operators using Java
Developed by: Yogeshvar M
RegisterNumber: 212222230180  
```

### Sourcecode.java
```java
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String name = sc.next();
        int age = sc.nextInt();
        float favNumber = sc.nextFloat();

        System.out.print("Hello, " + name);
        System.out.println("\nYou are " + age + " years old");
        System.out.printf("Your favorite number is %.2f", favNumber);
    }
}
```
## Output
<img width="590" height="274" alt="image" src="https://github.com/user-attachments/assets/ba5b6c25-e51a-4c9d-9676-e2ad0de39d07" />


## Result

The Java program demonstrating variables, data types, and different print statements (print, println, printf) was successfully executed.
