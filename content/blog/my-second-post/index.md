---
title: C# Interview Questions for beginners
date: "2019-08-15T23:46:37.121Z"
---

C# is a general-purpose, object-oriented programming language. The most recent stable version (at the time of writing this post) is C# 6.0 which was released in 2015.
In this post, we have compiled a list of c# interview questions and their answers for beginners as well as experienced users. These questions will help you to prepare for the interviews, for quick revision and provide strength to your technical skills.

1. What is C#?
C# (pronounced as CSharp) is an object-oriented, type safe and managed language that is compiled by .NET Framework to generate Microsoft Intermediate Language (MSIL).
2. What are the types of comment in C# with examples?
Single line
//This is a Single line comment
Multiple line (/* */)
/*This is a multiple line comment
We are in line 2 Last line of comment*/
XML Comments (///)
/// These comments can be used to briefly describe a class,
/// method, interface or any other entity.
3. Can multiple catch blocks be executed?
No. Multiple catch blocks can’t be executed. Once the proper catch code executed, the control is transferred to the finally block and then the code that follows the finally block gets executed.
4. What is the difference between public, static and void?
All these are access/type modifiers in C#.
public declared variables or methods are accessible anywhere in the application.
static declared variables or methods are globally accessible without creating an instance of the class. The compiler stores the address of the method as the entry point and uses this information to begin execution before any objects are created.
void is a type modifier which states that the method or variable does not return any value.
5. What is an object?
An object is an instance of a class through which we access the methods of that class. new keyword is used to create an object. A class that creates an object in memory will contain the information about the methods, variables and behavior of that class.
6. Define Constructors?
A constructor is a member function in a class that has the same name as its class. The constructor is automatically invoked whenever an object class is created. It constructs the values of data members while initializing the class.
public class Employee
{
int empid;
string empName;
public Employee(int a , string e)
{
empid = a;
empName = e;
}
}
7. What are Jagged Arrays?
The array which has elements of type array is called jagged array. The elements can be of different dimensions and sizes. We can also call jagged array as Array of arrays.
// Declare the array of two elements:
int[][] arr = new int[2][];
// Initialize the elements:
arr[0] = new int[5] { 1, 3, 5, 7, 9 };
arr[1] = new int[4] { 2, 4, 6, 8 };
8. What is the difference between ref & out parameters?
An argument passed as ref must be initialized before passing to the method whereas out parameter needs not to be initialized before passing to a method.
9. What is the use of using statement in C#?
The using block is used to obtain a resource and use it and then automatically dispose of when the execution of block completed.
10. What is serialization?
When we want to transport an object through network then we have to convert the object into a stream of bytes. The process of converting an object into a stream of bytes is called Serialization. For an object to be serializable, it should inherit ISerialize Interface.
De-serialization is the reverse process of creating an object from a stream of bytes.
For more questions and answers, you can refer to our website.
Thanks!
