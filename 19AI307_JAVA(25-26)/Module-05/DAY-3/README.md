# Ex.No:5(C)  FILE HANDLING USING JAVA

## QUESTION:
Write a program to overwrite the content of a file.

## AIM:
To write a Java program to overwrite the content of a file using FileWriter.

## ALGORITHM :
```
Start the program.

Import required classes (FileWriter, Scanner).

Take input content from the user.

Create a FileWriter object for the file (output.txt).

Write the input content into the file (overwrite mode).

Close the file writer.

Display success message.

End the program.
```
## PROGRAM:
```
Program to implement a File Handling using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
## SOURCE CODE:
```
import java.io.FileWriter;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String content = sc.nextLine();

        try {
            // Overwrite mode (default behavior)
            FileWriter fw = new FileWriter("output.txt");
            fw.write(content);
            fw.close();

            System.out.println("File content overwritten successfully.");
        } catch (Exception e) {
            System.out.println("Error occurred while writing file.");
        }

        sc.close();
    }
}
```
## OUTPUT:
<img width="894" height="173" alt="600900618-9d1217cc-2a94-4479-8787-d3f4e0adc3d3" src="https://github.com/user-attachments/assets/d72b2f7a-722b-471e-ad33-1690de262fd3" />

## RESULT:
The program successfully overwrites the existing content of a file named output.txt with new user-provided data using FileWriter.
