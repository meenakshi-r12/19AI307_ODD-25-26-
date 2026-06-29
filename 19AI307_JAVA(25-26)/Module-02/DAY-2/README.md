# Ex.No:2(B) METHODS

## QUESTION:
Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).

## AIM:
To write a Java program that demonstrates calling one method from another method to compute the cube of a number.

## ALGORITHM :
```
Start the program.
Import the necessary package 'java.util'
Create a method square(int x) that returns the square of x.
Create a method cube(int x) that calls square(x) and returns x * square(x).
In the main method, read an integer from the user.
Call the cube() method and display the result.
Stop the program.
```
## PROGRAM:
```
Program to implement a Methods using Java
Developed by: MEENAKSHI R
RegisterNumber:212224220062
```
## SOURCE CODE:
```
import java.util.*;
public class Main
{
    static int square(int x)
    {
        return x*x;
    }
    static int cube(int x)
    {
        return x*square(x);
    }
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int num=sc.nextInt();
        int result=cube(num);
        System.out.println(result);
    }
}
```
## OUTPUT:
<img width="453" height="163" alt="java22" src="https://github.com/user-attachments/assets/8da09d27-407b-40c1-bdc3-117ecfcec60c" />

## RESULT:
Thus, the Java program to calculate the cube of a number by calling the square method internally was successfully implemented and executed.
