# Ex.No:5(D) THREAD PRIORITY

## QUESTION:
Write a java program for determine the priority and name of the current thread.

## AIM:
To write a Java program to determine and display the name and priority of the current thread.

## ALGORITHM :
```
Start the program.

Import required classes (Scanner).

Read thread name from the user.

Get the current thread using Thread.currentThread().

Set the thread name using setName().

Retrieve and display thread priority using getPriority().

Retrieve and display thread name using getName().

Print the thread object details.

End the program.
```
## PROGRAM:
```
Program to implement a Thread Priority Concept using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
## SOURCE CODE:
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String threadName = sc.nextLine();

        Thread t = Thread.currentThread();
        t.setName(threadName);

        System.out.println("Priority of Thread: " + t.getPriority());
        System.out.println("Name of Thread: " + t.getName());
        System.out.println(t);

        sc.close();
    }
}
```
## OUTPUT:
<img width="564" height="178" alt="600901644-149ba57b-db7e-4982-966b-ceb434297053" src="https://github.com/user-attachments/assets/8da59f53-d3c5-4554-a55c-e5b2cf007ec1" />

## RESULT:
The Java program successfully determines and displays the current thread’s name and priority using the Thread class.
