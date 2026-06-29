# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to calculate the power of a given number.

## AIM:
To write a Java program to compute the power of a number using the Math.pow() function in Java.

## ALGORITHM :
```
Start the program.
Import the necessary package 'java.util'
Read the base value from the user.
Read the exponent value from the user.
Use the Math.pow(base, exponent) function to calculate the power.
Display the result.
Stop the program.
```
## PROGRAM:
```
Program to implement a Strings and Math Function using Java
Developed by: MEENAKSHI R
RegisterNumber:212224220062
```
## SOURCE CODE:
```
import java.util.*;

public class PowerCalculation {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double base = sc.nextDouble();
        double exponent = sc.nextDouble();
        double result = Math.pow(base, exponent);

        System.out.println(base + " raised to the power of " + exponent + " is: " + result);
    }
}
```
## OUTPUT: 
<img width="916" height="243" alt="Screenshot 2025-11-17 002442" src="https://github.com/user-attachments/assets/55fa5ec7-0983-4ab8-862e-6e74e3c0f2f6" />

## RESULT:
Thus, the Java program to calculate the power of a given number using Math function was successfully executed.
