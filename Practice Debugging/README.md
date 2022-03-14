# Practice Debugging
## How to debug for absolute beginners

the code we write as software developers doesn’t always do what we expected it to do ! When this happens,  the next task is to figure out why
by two way : 

1. just keep staring at our code for hours. 
2.  to use a debugging tool, or debugger.===>to find the exact point where you made a programming mistake
--------------------------------------
## Clarify the problem by asking yourself the right questions
Before you start debugging, make sure you've identified the problem you're trying to solve:
1. What did you expect your code to do?
2. What happened instead?
```
An exception is an unexpected event encountered when running code
```
You can examine each and every change or exception to your variables to discover exactly when and how incorrect values are assigned.

--------------------------------------------
## Examine your assumptions
Before you investigate a bug or an error, think of the assumptions that made you expect a certain result.
You may have a long list of possible assumptions! Here are a few questions to ask yourself to challenge your assumptions.

- Does your code contain any typos? 
- Did you make a change to your code and assume it is unrelated to the problem that you're seeing?
- Did you expect an object or variable to contain a certain value (or a certain type of value) that's different from what really happened?
- Do you know the intent of the code?

### By questioning your assumptions :
You may reduce the time it takes to find a problem in your code. You may also reduce the time it takes to fix a problem.

-----------------------------------------
```
#  Note
If it is difficult to identify the region of code where the problem occurs, set a breakpoint in code that runs before the problem occurs, and then use step commands until you see the problem manifest. You can also use tracepoints to log messages to the Output window. By looking at logged messages (and noticing which messages were not yet logged!), you can often isolate the region of code with the problem. You may have to repeat this process several times to narrow it down.
```



