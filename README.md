# LAB_ASSIGN-_JAVA_3

📘 Student Entry System (Java)

A Java console application demonstrating Custom Exceptions, Multithreading, Interfaces, and Robust Input Validation while collecting student details through user input.

🚀 Features
✔ Exception Handling

Custom exception: StudentNotFoundException

Handles:

Empty fields

Invalid numeric values

Invalid marks range

Unexpected input

✔ Multithreading

A separate thread (Loader) displays a loading animation using:

Thread t = new Thread(new Loader("Loading"));

✔ Interface Usage

RecordActions interface contains the method:

void addStudent() throws StudentNotFoundException;

✔ Strong Input Validation

Ensures name, email, and course cannot be empty

▶️ How to Run
Compile
javac StudentManager.java

Run
java StudentManager

Ensures marks must be between 0 and 100

<img width="842" height="502" alt="image" src="https://github.com/user-attachments/assets/c2d668bc-6581-4e3f-b880-92eda5c5bbf5" />





Catches incorrect numeric input using NumberFormatException

