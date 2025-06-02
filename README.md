# Java OOP Projects Collection

This repository contains multiple **Object-Oriented Programming (OOP)** projects in Java that demonstrate the use of core OOP principles like **inheritance**, **polymorphism**, **encapsulation**, **interfaces**, and **abstraction**. Each project is structured with proper class diagrams and real-life simulations.

---

## 🗂️ Projects Included

### 1. 🏧 ATM System
- **Description**: Simulates the working of an ATM machine with functionalities like checking balance, withdrawing money, and transferring funds.
- **Concepts Used**:
  - Inheritance (e.g., `Account` → `SavingsAccount`, `CheckingAccount`)
  - Interface (e.g., `Transaction`)
  - Polymorphism for performing different types of transactions
- **File**: `ATMSystem.java`

---

### 2. 🏥 Hospital Management System
- **Description**: Manages hospital operations like patient admission, doctor assignment, and treatment tracking.
- **Concepts Used**:
  - Inheritance (`Person` → `Doctor`, `Patient`, `Staff`)
  - Aggregation (e.g., `Doctor` assigned to many `Patients`)
  - Interface for generic person operations
- **File**: `HospitalManagementSystem.java`

---

### 3. 📚 Library Management System
- **Description**: A simple system to manage library books, accounts, and transactions such as book borrowing and returning.
- **Concepts Used**:
  - Inheritance (`User` → `Librarian`, `Member`)
  - Method Overriding (custom `login`/`display` methods)
  - Encapsulation (private fields with getters/setters)
- **File**: `LibraryManagementSystem.java`

---

## 🔧 Requirements

- Java JDK 8 or above
- Any Java IDE (e.g., IntelliJ IDEA, NetBeans, Eclipse)
- Basic knowledge of OOP concepts in Java

---

## ▶️ How to Run

Use the following commands in the terminal (or use your IDE to run the files):

```bash
javac ATMSystem.java
java ATMSystem

javac HospitalManagementSystem.java
java HospitalManagementSystem

javac LibraryManagementSystem.java
java LibraryManagementSystem
# Lab-Task
Lab Task
📚 Concepts Demonstrated
✅ Inheritance

✅ Method Overriding (Polymorphism)

✅ Method Overloading

✅ Interfaces

✅ Constructors

✅ Abstract Classes

✅ Encapsulation

📌 Notes
You can modify or extend each class according to your specific requirements.

These projects are designed for educational purposes and simplified for learning Java OOP.

Add GUI or file handling later to enhance the systems.

🤝 Contributing
Contributions are welcome! Feel free to fork this repo, improve the code, and submit a pull request.

