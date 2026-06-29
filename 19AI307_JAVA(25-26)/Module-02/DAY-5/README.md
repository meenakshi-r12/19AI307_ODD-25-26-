# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

## AIM:
To write a Java program that demonstrates the use of access modifiers through static and non-static methods in a class.

## ALGORITHM :
```
Start the program.
Import the necessary package 'java.util'
Create a class named Calculator.
Declare a non-static method add(int a, int b) to return the sum of two integers.
Declare a static method info() to display a message.
In the main() method, call the static method using the class name.
Create an object of the Calculator class and call the non-static method.
Display the output.
End the program.
```
## PROGRAM:
```
Program to implement a Access Modifiers using Java
Developed by: MEENAKSHI R
RegisterNumber:212224220062
```
## SOURCE CODE:
```
import java.util.Scanner;

class Calculator 
{
    static void show()
    {
        System.out.println("Calculator is ready");
    }
    int sum(int a,int b)
    {
        return a+b;
    }
}

class prog {
    public static void main(String[] args) 
    {
        Scanner sc=new Scanner(System .in);
        Calculator.show();
        int x=sc.nextInt();
        int y=sc.nextInt();
        Calculator calc=new Calculator();
        int result=calc.sum(x,y);
        System.out.println("Sum: "+result);
    }
}
```
## OUTPUT:
<img width="544" height="322" alt="java25" src="https://github.com/user-attachments/assets/1e81403a-5ea0-4350-b54b-d99120934f59" />

## RESULT:
Thus, a Java program to implement Access Modifiers with static and non-static methods was executed successfully.
