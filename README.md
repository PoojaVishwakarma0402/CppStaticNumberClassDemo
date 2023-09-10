# CppStaticNumberClassDemo

C++ Number Class Demo
This repository contains a simple C++ program that demonstrates the usage of a class named Number. The program explores the concepts of instance and static members within a class, providing insights into their behavior and usage.

About the Number Class
The Number class defined in this program has the following components:

Instance Variable x: An integer variable that stores a non-static value.

Static Variable y: A static integer variable shared by all instances of the class. It retains the same value across all instances.

Member Function set(): A non-static member function that displays the values of both the instance variable x and the static variable y for a given instance.

Static Member Function change(Number Temp): A static member function that takes an instance of the Number class as a parameter and displays the value of the instance variable x along with the static variable y.

Program Execution
In the main() function, three instances of the Number class (T1, T2, and T3) are created and initialized with x values of 0. The program then demonstrates the following:

Invoking the set() member function on T1 to display x and y values.
Invoking the static member function change(Number Temp) using the class name Number to display the x value of T1 along with the static variable y.
Attempting to call the change function on T1 directly (which would typically be a compilation error, but it's included for demonstration purposes).
Usage
Feel free to explore the code to gain a better understanding of how classes, instance variables, static variables, and member functions work in C++. You can use this code as a starting point for learning and experimenting with object-oriented programming in C++.

If you have any questions or suggestions, please don't hesitate to reach out.

