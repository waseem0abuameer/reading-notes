# What is Debugging?
Debugging is the process of finding errors during application execution.

## Clarify the problem by asking yourself the right questions
1. What did you expect your code to do?
2.  Does your code contain any typos?
3. Are you using the right method?
4. Are you using it correctly?
5. What happened instead?

# Step  code in debugging 
1. In Visual Studio, you can quickly set a breakpoint by clicking in the left margin next to a line of code. Or place the cursor on a line and press F9.
2. A breakpoint indicates where Visual Studio should pause your running code so you can take a look at the values of variables, or the behavior of memory, or the sequence in which code runs.
3. The debugger pauses on the line of code where you set the breakpoint.

========================================================================
# try/catch
The Common Language Runtime (CLR) catches exceptions not handled by catch blocks. If an exception is caught by the CLR, one of the following results may occur depending on your CLR configuration:

1. A Debug dialog box appears.
2. The program stops execution and a dialog box with exception information appears.
3. An error prints out to the standard error output stream.

=================================================

# Exception Handling
An exception is defined as an event that occurs during the execution of a program that is unexpected by the program code. The actions to be performed in case of occurrence of an exception is not known to the program. In such a case, we create an exception object and call the exception handler code. The execution of an exception handler so that the program code does not crash is called exception handling. Exception handling is important because it gracefully handles an unwanted event, an exception so that the program code still makes sense to the user.
 

## Keyword	Definition
1. try	Used to define a try block. This block holds the code that may 2. throw an exception.
3. catch	Used to define a catch block. This block catches the exception thrown by the try block.
4. finally	Used to define the finally block. This block holds the default code.
5. throw	Used to throw an exception manually.
