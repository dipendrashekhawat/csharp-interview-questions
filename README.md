# C# Interview Questions and Answers

> Hit :star: if you like the repo. PRs are appreciated.

### Table of Contents

|	SrNo	|	Question	|
|-----------|---------------|
|1	| [What is C#?](#what-is-C#)|
|2	| [What are the types of comments in C#?](#what-are-the-types-of-comments-in-C#)|
|3	| [Can multiple catch blocks be executed?](#can-multiple-catch-blocks-be-executed)|
|4	| [What is the difference between public, static and void?](#what-is-the-difference-between-public-static-and-void)|
|5	| [What is an object?](#what-is-an-object)|

1. ### What is C#?
C# (pronounced as CSharp) is an object-oriented, type safe and managed language that is compiled by .NET Framework 
to generate Microsoft Intermediate Language (MSIL).

2. ### What are the types of comment in C#?
There are 3 types of comments in C#

•	Single line
	//This is a Single line comment

•	Multiple line (/* */)
	/*This is a multiple line comment
 	We are in line 2Last line of comment*/
	
•	XML Comments (///)
	/// These comments can be used to briefly describe a class, 
	/// method, interface or any other entity.


3. ### Can multiple catch blocks be executed?

 No. Multiple catch blocks can’t be executed. Once the proper catch code executed, the control is transferred to the 
 finally block and then the code that follows the finally block gets executed.
 
4. ### What is the difference between public, static and void?
All these are access/type modifiers in C#.
public variables or methods are accessible anywhere in the application.
static variables or methods are globally accessible without creating an instance of the class. 
The compiler stores the address of the method as the entry point and uses this information to begin execution before any objects are created.
void is a type modifier which states that the method or variable does not return any value.

5. ### What is an object?
An object is an instance of a class through which we access the methods of that class. new keyword is used to create an object. 
A class that creates an object in memory will contain the information about the methods, variables and behaviour of that class.


 ```csharp
 public const double PI = 3.14;
 
 private static readonly _instance;
 ```
