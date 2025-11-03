Menu-Based Employee Management System Using File Handling
Objective

To create a menu-driven Java application that allows users to manage employee records using file handling and serialization.

Concepts Covered

File Handling: Reading and writing data to files.

Serialization: Saving and retrieving complex object data.

Menu-driven Programming: Using loops and conditionals for user interaction.

Data Persistence: Maintaining records between program executions.

Program Description

The program provides a menu with three options:

Add Employee

Prompts for employee details: ID, Name, Designation, Salary.

Saves the employee object into a file (employees.dat) via serialization.

Display All Employees

Reads all serialized employee objects from the file.

Displays them in a formatted table view.

Exit

Terminates the program gracefully.

Special Implementation

Uses a custom class AppendableObjectOutputStream to append objects without overwriting the file or corrupting stream headers.

Displays formatted employee details using printf().

Sample Menu
=== Employee Management System ===
1. Add Employee
2. Display All Employees
3. Exit
Enter your choice: 1
Enter Employee ID: 101
Enter Name: John
Enter Designation: Developer
Enter Salary: 55000
Employee added successfully!

=== Employee Management System ===
1. Add Employee
2. Display All Employees
3. Exit
Enter your choice: 2

ID         Name            Designation     Salary
-----------------------------------------------------------
101        John            Developer       55000.00

Key Classes/Methods

ObjectOutputStream, ObjectInputStream

FileOutputStream, FileInputStream

Serializable

Custom stream handling for appending objects

Usage

Compile and run the program:

javac EmployeeManagementSystem.java
java EmployeeManagementSystem

✅ Summary Across All Parts
Part	Title	Key Concepts
A	Sum of Integers	Autoboxing, Unboxing, String Parsing
B	Student Serialization	Object Serialization & Deserialization
C	Employee Management System	File Handling, Object Storage, Menu Interaction
