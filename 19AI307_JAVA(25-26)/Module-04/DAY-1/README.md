# Ex.No:4(A) EXCEPTION HANDLING

## QUESTION:
Write a program that reads two integers and divides the first by the second. Handle the case when division by zero occurs.

## AIM:
To write a Java program that performs integer division on two user-inputted numbers and handles potential division-by-zero errors using a try-catch block.

## ALGORITHM :
```
Start the program and initialize a Scanner object to receive user inputs.

Read two integer values from the user and store them in variables num1 and num2.

Open a try block to safely isolate the arithmetic operation from sudden runtime crashes.

Divide num1 by num2 inside the try block and print the successful calculation result.

Catch an ArithmeticException if the second number entered by the user is zero and print an error message.

Close the Scanner object to release memory resources and stop the program.
```
## PROGRAM:
```
Program to implement a Exception Handling using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
## SOURCE CODE:
```
import java.util.*;
public class DivisionProgram {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num1 = scanner.nextInt();
        int num2 = scanner.nextInt();

        try {
            int result = num1 / num2;
            System.out.println("Result: " + result);
        } catch (ArithmeticException e) {
            System.out.println("Error: Division by zero");
        }

        scanner.close();
    }
}
```
## OUTPUT:
<img width="651" height="277" alt="600884924-8a54e048-c61b-4cb7-b36c-83b6a691dba9" src="https://github.com/user-attachments/assets/1616b8f0-b5b1-43f6-883c-7576c016f3e4" />

## RESULT:
Thus the java program to implement the exception handling was executed successfully.
