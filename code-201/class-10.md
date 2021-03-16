# ERROR HANDLING & DEBUGGING

lets help you learn how to find the errors in your code.

To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

## EXECUTION CONTEXTS

The JavaScript interpreter uses the concept of execution contexts.There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

## the stack

the javascript interpreter processes one line of code at a time when a ststement needs data from anthor function,it stacks the new function of the current task.

## UNDERSTANDING SCOPE

In the interpreter, each execution context has its own va ri ables object.It holds the variables, functions, and parameters available within it.Each execution context can also access its parent's v a ri ables object.

## UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception.At that point, the interpreter stops and looks for exception-handling code.

## ERROR OBJECTS

Error objects can help you find where your mistakes are and browsers have tools to help you read them.

## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE

The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be.

BREAKPOINTS
You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.