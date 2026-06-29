# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a haunted house, lights turn on or off based on the hour of entry:

If the hour is even and between 2 and 6 (inclusive), lights flicker.

If the hour is odd and between 7 and 11, lights stay off.

If the hour is 12, lights turn red.

Otherwise, the house is dark.

## AIM:
To write a Java program that uses conditional statements to determine the state of lights in a haunted house based on the hour of entry.

## ALGORITHM :
```
Start the program.

Import the necessary package java.util.*.

Create a Scanner object to read the hour input from the user.

Read the hour as an integer.

Check if the hour is even and between 2 and 6 (inclusive):

Display “Lights flicker”.

Else if the hour is odd and between 7 and 11:

Display “Lights stay off”.

Else if the hour is 12:

Display “Lights turn red”.

Display “The house is dark”.

End the program.
```
## PROGRAM:
```
Program to implement a conditional statement using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
Sourcecode.java:
```
import java.util.*;
public class Demo
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
       if (a >= 2 && a <= 6 && a % 2 == 0) {
            System.out.println("Lights flicker");
        } else if (a>= 7 && a <= 11 && a % 2 != 0) {
            System.out.println("Lights off");
        } else if (a == 12) {
            System.out.println("Lights red");
        } else {
            System.out.println("Dark house");
        }
    }
}
```
## OUTPUT:
<img width="486" height="294" alt="514249233-a64529b4-061c-436d-8ea4-55157b6e41b9" src="https://github.com/user-attachments/assets/7c7a690e-3413-4544-9971-e507abd3e402" />

## RESULT:
Thus, the Java program to implement conditional statements for the haunted house lighting system was successfully executed.
