# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to find the index of a given element in an array.

## AIM:
To write a Java program that finds the index position of a specified element from a given array.

## ALGORITHM :
```
Start the program.
Import the necessary package 'java.util'
Read the size of the array from the user.
Create an array of the given size.
Read the array elements from the user and store them in the array.
Read the element to be searched.
Traverse the array and compare each element with the search element.
If matched, print the index position and terminate.
If not found, display "Element not found".
Stop the program.
```
## PROGRAM:
```
Program to implement a Array concept using Java
Developed by: MEENAKSHI R
RegisterNumber:212224220062
```
## SOURCE CODE:
```
import java.util.*;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++)
        {
            arr[i]=sc.nextInt();
        }
        int key=sc.nextInt();
        int index=-1;
        for(int i=0;i<n;i++)
        {
            if(arr[i]==key)
            {
                index=i;
                break;
            }
        }
        
        if(index!=-1)
        {
            
            System.out.println(index);
        }
        else{
            System.out.println("Element not found");
        }
    }
}
```
## OUTPUT
<img width="537" height="516" alt="output" src="https://github.com/user-attachments/assets/0f2555f3-2575-48e5-a64e-24249aff469b" />

## RESULT:
Thus, the Java program to find the index of a given element in an array was successfully executed.
