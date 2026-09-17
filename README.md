# saisankavi-oop-IA1-
Harvestable Interface – WheatCrop

📌 Project Title

Create an Interface Harvestable with Method "harvest()" and Implement it in a Class "WheatCrop"

📖 Description

This Java program demonstrates the concept of interfaces and implementation in Object-Oriented Programming.

An interface named "Harvestable" is created with a method called "harvest()". The "WheatCrop" class implements this interface and provides the implementation for the "harvest()" method.

The program shows how a class can use an interface to achieve abstraction and define a common behavior.

🎯 Objective

- To understand the concept of interfaces in Java.
- To implement an interface method in a class using the "implements" keyword.

🧠 Concepts Used

1. Interface

An interface in Java is used to define a set of methods that a class must implement.

In this program:

interface Harvestable {
    void harvest();
}

The "Harvestable" interface contains the "harvest()" method.

2. Implements Keyword

The "implements" keyword is used when a class provides the implementation of an interface.

class WheatCrop implements Harvestable

This means that "WheatCrop" must provide the implementation of the "harvest()" method.

3. Method Overriding

The "WheatCrop" class overrides the "harvest()" method and provides its own behavior.

@Override
public void harvest() {
    System.out.println("Wheat crop is ready for harvesting.");
}

💻 Program

interface Harvestable {
    void harvest();
}

class WheatCrop implements Harvestable {

    @Override
    public void harvest() {
        System.out.println("Wheat crop is ready for harvesting.");
    }
}

public class Main {
    public static void main(String[] args) {

        WheatCrop wheat = new WheatCrop();

        wheat.harvest();
    }
}

⚙️ How the Program Works

1. The "Harvestable" interface is created.
2. The interface contains the abstract method "harvest()".
3. The "WheatCrop" class implements the "Harvestable" interface.
4. The "harvest()" method is overridden inside the "WheatCrop" class.
5. An object of "WheatCrop" is created in the "main()" method.
6. The "harvest()" method is called using the object.
7. The program displays the harvesting message.

🔄 Program Flow

Start
  ↓
Create Harvestable Interface
  ↓
Declare harvest() Method
  ↓
Create WheatCrop Class
  ↓
Implement Harvestable Interface
  ↓
Override harvest() Method
  ↓
Create WheatCrop Object
  ↓
Call harvest()
  ↓
Display Output
  ↓
End

🖥️ Output

Wheat crop is ready for harvesting.

📁 Project Structure

Harvestable-WheatCrop/
│
├── Main.java
└── README.md

🛠️ Requirements

- Java JDK 8 or above
- Any Java-supported IDE or text editor
- Command Prompt / PowerShell / Terminal

▶️ How to Run

Step 1: Compile the program

Open the terminal in the project folder and run:

javac Main.java

Step 2: Run the program

java Main

Expected Output

Wheat crop is ready for harvesting.

🌾 Real-World Application

The concept can be extended to different types of crops. For example, "RiceCrop", "CornCrop", and "SugarcaneCrop" can also implement the "Harvestable" interface and provide their own harvesting behavior.

This demonstrates how interfaces can be used to define common behavior while allowing different classes to implement that behavior in their own way.

📚 Conclusion

This program demonstrates how to create and implement an interface in Java. The "Harvestable" interface defines the "harvest()" behavior, while the "WheatCrop" class provides its implementation. This helps understand abstraction, interfaces, and method overriding in Java.

👨‍💻 Author

SAISANKAVI

---

⭐ This project is created for learning and demonstrating Java Object-Oriented Programming concepts.
