Sum of Integers Using Autoboxing and Unboxing
Objective

This program demonstrates the use of autoboxing, unboxing, and string parsing in Java to compute the sum of integers entered by the user.

Concepts Covered

Autoboxing: Automatic conversion of primitive int to Integer when adding to a collection.

Unboxing: Automatic conversion of Integer back to int during arithmetic operations.

String Parsing: Conversion of user input strings to integer values using Integer.parseInt().

Program Description

The program accepts a list of integers as string input from the user (space-separated).

Each string is parsed into an Integer object and stored in an ArrayList<Integer>.

Using an enhanced for-loop, each Integer value is unboxed and summed.

The final total sum is displayed on the console.
Sample Input/Output
Enter integers separated by spaces:
10 20 30 40

Sum of integers: 100

Key Classes/Methods

ArrayList<Integer>

Integer.parseInt()

Enhanced for-loop for unboxing

Usage

Compile and run the program:

javac SumOfIntegers.java
java SumOfIntegers
