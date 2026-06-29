# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:

Lovely has just started learning Java and is very excited about how to display messages on the screen. Her first mission is to understand how different types of print statements work:

System.out.print() → prints on the same line

System.out.println() → prints and moves to the next line

System.out.printf() → prints formatted output

## AIM:
To write a Java program that demonstrates the use of variables, data types, operators, and different print statements (print, println, and printf).

## ALGORITHM :
Start the program.
Import the required package java.util.* (optional).
Declare variables of different data types (int, float, char, String).
Perform simple arithmetic operations using operators.
Use System.out.print() to display output on the same line.
Use System.out.println() to display output on the next line.
Use System.out.printf() to print formatted output.
End the program.
## PROGRAM:
/*
Program to implement variables and Operators using Java
Developed by: HARITHA RAMESH
RegisterNumber: 212223100011
*/
## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        String name=sc.next();
        int age=sc.nextInt();
        double num=sc.nextDouble();
        System.out.println("Hello, "+name);
        System.out.println("You are "+age+" years old");
        System.out.printf("Your favorite number is %.2f ",num);
    }
}
```
## OUTPUT:
<img width="766" height="385" alt="514251561-8ca3a2e4-e913-4c3f-a8bf-73827075ab57" src="https://github.com/user-attachments/assets/1a0a6c9b-d6d7-47d2-ac09-cf6a3d21c5ef" />

## RESULT:
Thus, the Java program demonstrating variables, data types, operators, and print statements was successfully executed.
