erialization and Deserialization of a Student Object
Objective

To implement serialization and deserialization in Java for persisting and retrieving an object’s state.

Concepts Covered

Serialization: Converting an object into a byte stream for storage.

Deserialization: Reconstructing an object from its stored byte stream.

Serializable Interface: Enables an object to be serialized.

Program Description

A Student class is defined with fields studentID, name, and grade.

The class implements Serializable to allow object serialization.

The program:

Creates a Student object.

Serializes (saves) the object to a file (student.dat).

Deserializes (reads) the object back from the file.

The deserialized object’s data is displayed to verify successful restoration.

Sample Output
Student object has been serialized to student.dat

Deserialized Student object:
Student ID: 101
Name: Alice
Grade: 9.2

Key Classes/Methods

ObjectOutputStream / ObjectInputStream

FileOutputStream / FileInputStream

Serializable interface

serialVersionUID

Usage

Compile and run the program:

javac StudentSerialization.java
java StudentSerialization
