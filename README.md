# saisankavi-oop-IA1-
Problem B: Harvestable Interface – WheatCrop

Student Details

- Name: Saisankavi P
- Register Number: 113024148085
- Problem: B

1. Title

Create an interface "Harvestable" with method "harvest()". Implement it in a class "WheatCrop".

2. Objective

To understand the concept of interfaces in Java and implement an interface method in a class.

3. Description

This Java program demonstrates the use of an interface named "Harvestable". The interface contains a method called "harvest()". The "WheatCrop" class implements the interface and provides the implementation of the "harvest()" method.

When the program runs, it creates a "WheatCrop" object and calls the "harvest()" method to display the harvesting messages.

4. Concepts Used

Interface

An interface is a blueprint that defines methods a class must implement. In this program, the "Harvestable" interface contains the "harvest()" method.

Implements Keyword

The "implements" keyword is used to implement an interface in a class.

Method Overriding

The "WheatCrop" class provides the implementation of the "harvest()" method declared in the "Harvestable" interface.

Object Creation

An object of the "WheatCrop" class is created in the "main()" method to call the harvesting method.

5. Java Program

// Problem B
// Name : Saisankavi P
// Reg No : 113024148085

interface Harvestable {
    void harvest();
}

class WheatCrop implements Harvestable {

    public void harvest() {
        System.out.println("Wheat crop is ready for harvesting.");
        System.out.println("Harvesting wheat crop...");
    }
}

public class Main {
    public static void main(String[] args) {

        WheatCrop wheat = new WheatCrop();

        wheat.harvest();
    }
}

6. Algorithm

1. Start the program.
2. Create an interface named "Harvestable" with a method "harvest()".
3. Create a class named "WheatCrop" that implements the "Harvestable" interface.
4. Define the "harvest()" method inside the "WheatCrop" class.
5. Display the message "Wheat crop is ready for harvesting."
6. Display the message "Harvesting wheat crop..."
7. Create an object of the "WheatCrop" class.
8. Call the "harvest()" method using the object.
9. Stop the program.

7. Output

Wheat crop is ready for harvesting.
Harvesting wheat crop...

8. Sample Output Screenshot

The program output can be captured from the Java terminal or Google Colab and uploaded to the repository as an image.

9. How to Run

Requirements

- Java Development Kit (JDK)
- Java-supported IDE or terminal

Compile the Program

Save the program as "Main.java" and run:

javac Main.java

Execute the Program

java Main

10. Project Structure

Harvestable-WheatCrop/
│
├── Main.java
└── README.md

11. Real-World Application

The "Harvestable" interface can be used to define common harvesting behavior for different crops. Other classes such as "RiceCrop" and "CornCrop" can implement the same interface and provide their own harvesting methods.

12. Conclusion

The program successfully demonstrates the creation and implementation of an interface in Java. The "WheatCrop" class implements the "Harvestable" interface and displays the harvesting messages when the "harvest()" method is called.
