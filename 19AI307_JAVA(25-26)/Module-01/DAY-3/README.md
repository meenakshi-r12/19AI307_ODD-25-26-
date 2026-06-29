# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Construct a right-angled triangle star pattern using for loop.

## AIM:
To write a Java program using looping statements to print a right-angled triangle star pattern based on user input.

## ALGORITHM :
```
Start the program.

Import the necessary package 'java.util'

Read the number of rows from the user.

Use an outer loop to iterate through each row.

Use an inner loop to print stars (*) for each row.

Move to the next line after printing stars for each row.

End the program.
```
## PROGRAM:
```
Program to implement a Looping Statement using Java
Developed by: MEENAKSHI R
RegisterNumber:212224220062
```
## SOURCE CODE:
```
import java.util.*;
public class TrianglePattern
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for (int i = 1; i <= n; i++) 
        {         
            for (int j = 1; j <= i; j++) 
            {      
                System.out.print("* ");
            }
            System.out.println();              
        }
    }
}
```
## OUTPUT:
<img width="399" height="395" alt="514252611-07286d0c-5174-4702-8d58-34b630bd23d6" src="https://github.com/user-attachments/assets/64e29401-d5c5-4395-b062-41cd564ea130" />

## RESULT:
Thus, the Java program using looping statements to print a right-angled triangle star pattern was successfully written, executed, and verified.
