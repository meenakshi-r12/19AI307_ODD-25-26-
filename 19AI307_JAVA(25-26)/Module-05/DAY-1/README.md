# Ex.No:5(A) INPUTSTREAMREADER 

## QUESTION:
Write a program to demonstrate chaining of streams (BufferedReader on top of InputStreamReader on top of System.in)

## AIM:
To write a Java program to demonstrate chaining of streams using BufferedReader on top of InputStreamReader on top of System.in for reading user input.

## ALGORITHM :
```
Start the program.

Create a BufferedReader object using InputStreamReader(System.in).

Read the user’s name using readLine()

Read the user’s age using readLine() and convert it to integer using Integer.parseInt().

Display the entered user details.

Stop the program.
```
## PROGRAM:
```
Program to implement a InputStreamReader using Java
Developed by: MEENAKSHI R
RegisterNumber:  212224220062
```
## SOURCE CODE:
```
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class Main {
    public static void main(String[] args) throws IOException {

        BufferedReader br = new BufferedReader(
                                new InputStreamReader(System.in));

        String name = br.readLine();
        int age = Integer.parseInt(br.readLine());

        System.out.println("--- User Details ---");
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}
```
## OUTPUT:
<img width="481" height="382" alt="600897942-2a54383a-5d16-483f-8349-d1a1777df567" src="https://github.com/user-attachments/assets/3567eab7-ada5-407b-878d-14e63eebb1e6" />

## RESULT:
The program successfully demonstrates chaining of streams in Java using BufferedReader, InputStreamReader, and System.in to read input from the user and display the entered details.
