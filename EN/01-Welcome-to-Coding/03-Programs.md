[slide]
 
# Programs

**Programs** in C# consist of **sequence of commands**, each staying at separate line, ending with `;` at the end of the line. Example **program of 3 commands** intended to print some text and evaluate an expression:

```cs
Console.WriteLine("Welcome to coding");
Console.WriteLine(3 * 5 + 2);
Console.WriteLine("Have a nice day");
```

The above program will print the following **output**:
```
Welcome to coding
17
Have a nice day
```

**Run** the above program, modify it, play with it. Can you **add a new command** to print your name after the last command?

## The Full C# Pogram Syntax

If you copy the above program of 3 lines in a console C# project in **Visual Studio** or in sme online code runner (like .NET Fiddle), you will notice that it will not

[/slide]


[slide]
# Exercises: Simple Programs

In this exercise we shall **write simple programs** in C# to print texts and calculate expressions.


# Exercise: Name and Expression

[code-task title="Print Name + Expression" executionStrategy="csharp-dot-net-core-code"]

[code-editor language=csharp]
[/code-editor]

[task-description]
Write a program to **print your name** at the first line and calculate and **print the expression** `5 + 3` at the second line.

The expected **output** from your program might look like this:
```
Maria
8
```
Another valid **output** example:
```
Peter
8
```
[/task-description]

[code-io /]

[/code-task]


# Exercise: Calculations

[code-task title="Calculations" executionStrategy="csharp-dot-net-core-code"]

Write a program to **calculate** and print the value of the following expressions:
  - 5 + 3 * 2
  - 4 * (2 + 3)
  - (2 + 5) * (8 - 2) / 7

Print the value of each expression on a separate line. The expected **output** from your program should look like this:
```
11
20
6
```

[code-editor language=csharp]
[/code-editor]

[/code-task]

[/slide]
