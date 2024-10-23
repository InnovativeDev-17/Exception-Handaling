# Exception-Handaling
Exception Handling
Objective:
To implement programs that utilize exception handling.

Overview:
Exception handling is a programming mechanism that allows developers to manage errors or unexpected situations that arise during a program's execution. Instead of crashing or generating incorrect results, it provides a structured way to catch and handle these errors. This is achieved through the use of constructs like try, catch, and throw, allowing programs to either continue running or terminate gracefully in the face of errors.

Key Concepts:

Exceptions: Events that interrupt the normal execution flow due to errors.
Try Block: A section of code that may generate an exception.
Catch Block: Specifies how to handle particular types of exceptions.
Throw Statement: Used to indicate that an error has occurred.
Standard Exception Classes: Predefined exception types in C++, such as std::runtime_error and std::invalid_argument.
Algorithm: Division by Zero Error Handling

Start.
Declare variables n1, n2, and ans to hold two numbers and the result.
Prompt the user to "Enter the values for numbers 1 and 2."
Read the user input into n1 and n2.
Try the following:
Check if n2 is equal to 0:
If true, throw an exception with the value of n2.
If false, calculate ans as n1 / n2.
Print the result as "The answer is [result]."
Catch any exceptions:
If an exception occurs, print "ERROR: Division by [number]."
End.
