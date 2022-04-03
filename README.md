# Get-to-Know-More-About-Python
## Looping
Looping is the process of repeating the execution of one or more statement blocks without stopping, as long as the reference condition is met. Usually, a variable for iteration is set up or a marker variable for when the loop will be terminated. 
1.	For Loop, for is a form of looping where the block statement will be executed repeatedly according to the specified number of iterations.
2.	While Loop, The while loop is an indefinite or even infinite loop. A block of code will be executed continuously as long as a condition is met. If a condition is not met in the 10th iteration, the loop will stop.
## Break, Continue, Pass Statement
1.	The break statement in Python terminates the current loop and resumes execution at the next statement, just like the traditional break found in C. The most common use for the break is when some external condition is triggered requiring a hasty exit from a loop. The break statement can be used in both a while and for a loop.
2.	The continue statement in Python returns the control to the beginning of the while loop. The continue statement rejects all the remaining statements in the current iteration of the loop and moves the control back to the top of the loop. The continue statement can be used in both a while and for a loop.
3.	Pass Error, is the process of passing errors without stopping a program from running.
## List Comprehension
List Comprehension is a feature of Python lists that is used to create a new list from the elements of an existing list. A list comprehension is a programing language construct for creating a list based on existing lists
Two types of errors based on their occurrence :
1.	Syntax Error, Syntax errors are perhaps the most common kind of complaint you get while you are still learning Python. 
2.	Exceptions, An error that is detected during execution and is not unconditionally fatal, Even if a statement or expression is syntactically correct
## Exception Handling
An exception can be defined as an unusual condition in a program resulting in an interruption in the flow of the program. Python provides a way to handle the exception so that the code can be executed without any interruption. If we don’t handle the exception, the interpreter doesn’t execute all the existing code after the exception.
## Function
The function is a process that relates between an input and an output. It's also a way to organize codes for reusability. Python provides built-in functions, but we can still make our own functions.
1.	Function Name,  An identifier by which the function is called
2.	Arguments, Contains a list of values passed to the function
3.	Indentation, Function body must be indented
4.	Function Body, This is executed each time the function is called
5.	Return Value, Ends function call & sends data back to the program
## Difference between pass by value and pass by reference
-	Pass by Reference means that the argument passed to the function is a reference to a variable that already exists in memory.  Any operation performed by the function on the variable will be directly reflected by the function caller.
- Pass by Value means that the function is provided with a copy of the argument variable passed to it by the caller.  So, the original variable stays intact and all changes made are to a copy of the same variable and stored at different memory locations.
