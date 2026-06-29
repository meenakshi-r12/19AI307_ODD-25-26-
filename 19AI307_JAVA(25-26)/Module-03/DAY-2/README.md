# Ex.No:3(b) POLYMORPHISM

## QUESTION:
Write a Java program that calculates the area of different shapes using method overloading. Create a class AreaCalculator with:

area(int side) for square

area(int length, int breadth) for rectangle

area(double radius) for circle

<img width="447" height="180" alt="516219517-28afedde-02fe-4562-8c03-3310286a0ab0" src="https://github.com/user-attachments/assets/6e0ee9ec-c916-4116-a537-334c2eba6bbd" />

## AIM:
Create an AreaCalculator class using method overloading to calculate areas of a square, rectangle, and circle.

## ALGORITHM :
```
Start and import Scanner.

Create prog class with overloaded area() methods for square, rectangle, and circle.

Read side, length & breadth, and radius from the user.

Call the appropriate area() method for each shape.

Display the areas and end the program.
```
## PROGRAM:
```
Program to implement a Polymorphism using Java
Developed by: MEENAKSHI R
RegisterNumber: 212224220062
```
## SOURCE CODE:
```
import java.util.Scanner;

class prog {

    void area(int side) {
        System.out.println("Area of square: " + (side * side));
    }

    void area(int length, int breadth) {
        System.out.println("Area of rectangle: " + (length * breadth));
    }

    void area(double radius) {
        double result = Math.PI * radius * radius;
        System.out.println("Area of circle: " + result);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        prog obj = new prog();

        int side = sc.nextInt();
        obj.area(side);

        int length = sc.nextInt();
        int breadth = sc.nextInt();
        obj.area(length, breadth);

        double radius = sc.nextDouble();
        obj.area(radius);

        sc.close();
    }
}
```
## OUTPUT:
<img width="825" height="372" alt="516220625-c42bf11f-b5fd-4d8a-83ed-5fa4850d2192" src="https://github.com/user-attachments/assets/5929220a-aa1f-410b-be2d-9fda3ebfb0ef" />

## RESULT:
The program displays the area of the chosen shape based on the input values.
