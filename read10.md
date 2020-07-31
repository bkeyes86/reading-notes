## Call Stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions. ##
## When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function ##
## If the stack takes up more space than it had assigned to it it results in a stack overflow error ##
## Since the call stack is single functions execution is done one at a time from top to bottom it means the call stack is synchronous ##
## LIFO = Last in First Out ##
## The call stack maintains a record of the position of each stack frame. It knows the next function to be executed and will remove it after execution this is what makes code execution in javascript synchronous ##
## A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point the browser has a maximum stack call that it can accomodate before throwing a stack error.##
## Types of errors Reference, Syntax, Range, Type ##

