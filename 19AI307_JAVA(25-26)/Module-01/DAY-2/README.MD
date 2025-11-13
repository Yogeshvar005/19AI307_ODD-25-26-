# Ex.No: 1(B) — Conditional Statement
## Question

Write a Java program to assign an exam room based on gender and subject code.

Room assignment rules:

• Male taking subject 1 or 2 → print "A"

• Female taking subject 1 → print "B"

• Female taking subject 2 → print "C"

• All others (valid subject inputs) → print "Admin"

• Any invalid gender/subject input → print "Invalid"

Example:
## Aim

To write a Java program that implements conditional statements to assign exam rooms based on user-provided gender and subject code.

## Algorithm

• Start the program.
• Import the necessary package java.util.*.
• Read gender input as a character.
• Read subject code as an integer.
• Convert gender to lowercase.
• Use conditional statements (if–else) to check:
      ・ Male with subject 1 or 2 → Room A
      ・ Female with subject 1 → Room B
      ・ Female with subject 2 → Room C
      ・ Valid inputs not listed above → Admin
      ・ Invalid gender/subject → Invalid
• Print the appropriate room.
• End the program.

## Program
```
Program to implement a conditional statement using Java
Developed by: Yogeshvar M
RegisterNumber: 212222230180 
```

### Source Code
```java
import java.util.Scanner;

public class ExamRoomAssignment {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        char gender = sc.next().toLowerCase().charAt(0);  
        int subject = sc.nextInt();

        String room;

        if (gender == 'm') {
            if (subject == 1 || subject == 2) {
                room = "A";
            } else if (subject >= 1 && subject <= 9) {
                room = "Admin";
            } else {
                room = "Invalid";
            }
        } else if (gender == 'f') {
            if (subject == 1) {
                room = "B";
            } else if (subject == 2) {
                room = "C";
            } else if (subject >= 1 && subject <= 9) {
                room = "Admin";
            } else {
                room = "Invalid";
            }
        } else {
            room = "Invalid";
        }

        System.out.println(room);

        sc.close();
    }
}
```
## Output

## Result

The Java program to implement conditional statements and assign exam rooms based on gender and subject code was successfully executed.


