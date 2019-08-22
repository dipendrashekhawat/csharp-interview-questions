# C# Interview Questions and Answers

> Hit :star: if you like the repo. PR's are appreciated.

### Table of Contents

|	SrNo	|	Question	|
|-----------|---------------|
|1	| [What are the access modifiers in C#?](#what-are-the-access-modifiers-in-C#)|
|2	| [What is the difference between readonly and const?](#what-is-the-difference-between-readonly-and-const)|


1. ### What are the access modifiers in C#?

There are 5 access modifiers in C# - public, private, protected, internal, protected internal.

2. ### What is the difference between readonly and const?

 While declaring a const we need to specify the value at the time of declaration. For readonly variable, the value can be assigned at run-time. 

 ```csharp
 public const double PI = 3.14;
 
 private static readonly _instance;
 ```
