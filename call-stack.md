# call stack

- A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions.
- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

- In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue.
- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.
-  A call stack is single-threaded. Meaning it can only do one thing at a time.
- Code execution is synchronous.
- A function invocation creates a stack frame that occupies a temporary memory.
- It works as a LIFO — Last In, First Out data structure.

## JavaScript error messages
-  `foo is not defined` - when you try to use a variable that is not yet declared you get this type os errors.
- `Unexpected token` -  can be solved by just fixing the syntax.
- `RangeError: Invalid array length` - the array length you tried to use is wrong.
- `Uncaught TypeError: Cannot read property 'baz' of undefined` - shows up when the types (number, string and so on) you are trying to use or access are incompatible.
