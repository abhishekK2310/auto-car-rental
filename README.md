🚗 Car Rental System in Java
📌 Project Overview

This project is a Car Rental System built using Object-Oriented Programming (OOP) principles in Java.
It simulates a real-world car rental service where customers can rent cars, and the system keeps track of rentals.

The project demonstrates OOP concepts like:

Encapsulation

Abstraction

Constructors

Getters & Setters

Object Associations (Customer ↔ Car ↔ Rental)

🛠 Features

Add new cars to the rental system

Rent a car if available

Track rented cars with rental details (customer, car, duration)

Prevent renting if the car is already booked

Print rental records

📂 Project Structure
CarRentalSystem/
│
├── Car.java          # Represents a Car with availability status
├── Customer.java     # Represents a Customer
├── Rental.java       # Represents a Rental record (Car + Customer + Days)
├── CarRentalSystem.java  # Main system to manage rentals
└── Main.java         # Entry point of the program

💻 Technologies Used

Java (Core Java, OOP Concepts)

IntelliJ IDEA 

🚀 How to Run

Clone this repository:

git clone https://github.com/abhishekK2310/Car-Rental-System.git


Open the project in IntelliJ IDEA / Eclipse.

Compile and run Main.java.

The console will simulate the car rental system.

📸 Sample Output
Available Cars: 
Car: Honda City, Available: true
Car: Hyundai Creta, Available: true

Customer John rents Honda City for 5 days.

Car: Honda City, Available: false
Car: Hyundai Creta, Available: true

🎯 Learning Outcomes

Understanding how to structure a project using multiple classes

Applying Encapsulation & Abstraction in a real-world example

Creating associations between objects (Car ↔ Customer ↔ Rental)

Managing object states (available / rented)

## 📧 Contact

Abhishek Kumar - [GitHub @abhishekK2310](https://github.com/abhishekK2310)

Feel free to reach out with any questions or feedback!
