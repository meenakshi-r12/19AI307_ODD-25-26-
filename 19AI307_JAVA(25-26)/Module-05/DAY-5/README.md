# Ex.No:5(E) MULTITHREADING -SYNCHRONIZATION

## QUESTION:
Maintain two int variables a and b, read their initial values from user. Use synchronized block to swap them and print swapped values.

Input:

Two lines: a and b values

Output:

a = <swapped_a>

b = <swapped_b>

For example:

Input Result 5 10 a = 10 b = 5

## AIM:
To write a Java program to swap two integer values using a synchronized block to ensure thread-safe operation.

## ALGORITHM :
```
Start the program.

Read two integer values a and b from the user.

Create a shared object for synchronization.

Use a synchronized block on the shared object.

Inside the block, swap the values of a and b.

Print the swapped values.

End the program.
```
## PROGRAM:
```
Program to implement a Synchronization concept using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
## SOURCE CODE:
```
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int a = sc.nextInt();
        int b = sc.nextInt();

        final Object lock = new Object();

        synchronized (lock) {
            int temp = a;
            a = b;
            b = temp;
        }

        System.out.println("a = " + a);
        System.out.println("b = " + b);

        sc.close();
    }
}
```
## OUTPUT:
<img width="304" height="256" alt="600904488-091dc42e-9423-476c-9ace-dfb98a457dd7" src="https://github.com/user-attachments/assets/90e0d957-9171-478c-9533-916f45bdd686" />

## RESULT:
The Java program successfully demonstrates the use of a synchronized block to safely swap two integer values and display the swapped output.
