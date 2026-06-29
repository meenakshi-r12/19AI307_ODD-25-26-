# Ex.No:4(D) DESIGN PATTERN -- ABSTRACT FACTORY

## QUESTION:
You are asked to simulate a simple Shape Drawing Tool using the Factory Design Pattern in Java.

You will implement a Shape interface with concrete classes for different shapes (Circle, Square, Rectangle). Using a ShapeFactory, your program will take shape names from user input and draw them accordingly. If the shape is unknown, print an error message.

## AIM:
To implement the Factory Design Pattern in Java to create and draw different shapes like Circle, Square, and Rectangle based on user input.

## ALGORITHM :
```
Start the program and create a ShapeFactory object.

Read shape name input from the user in a loop.

If input is "exit", stop the program.

Pass input to ShapeFactory to create the required shape object.

If shape is valid, call the draw() method; otherwise print an error message.

Repeat steps 2–5 until exit.

End the program.
```
## PROGRAM:
```
Program to implement a Abstract Factory Pattern using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
## SOURCE CODE:
```
import java.util.*;

interface Shape {
    void draw();
}

class Circle implements Shape {

    public void draw() {
        System.out.println("Drawing Circle");
    }
}

class Square implements Shape {

    public void draw() {
        System.out.println("Drawing Square");
    }
}

class Rectangle implements Shape {

    public void draw() {
        System.out.println("Drawing Rectangle");
    }
}

class ShapeFactory {

    public Shape getShape(String shapeType) {

        if (shapeType.equalsIgnoreCase("circle")) {
            return new Circle();
        }
        else if (shapeType.equalsIgnoreCase("square")) {
            return new Square();
        }
        else if (shapeType.equalsIgnoreCase("rectangle")) {
            return new Rectangle();
        }

        return null;
    }
}

public class Main {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        ShapeFactory factory = new ShapeFactory();

        while (true) {

            String input = sc.nextLine();

            if (input.equalsIgnoreCase("exit")) {
                break;
            }

            Shape shape = factory.getShape(input);

            if (shape != null) {
                shape.draw();
            }
            else {
                System.out.println("Invalid shape: " + input);
            }
        }

        sc.close();
    }
}
```
## OUTPUT:
<img width="509" height="374" alt="600893455-d39a2b9d-5292-45ca-9ce3-9ce109940071" src="https://github.com/user-attachments/assets/515859a6-8dc5-4ce2-83e2-72633382bddf" />

## RESULT:
Thus, the program to implement the Factory Design Pattern for creating and drawing different shapes (Circle, Square, Rectangle) based on user input was successfully executed and the output was obtained.
