# TESTS

- Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. 

- Test-Driven Development is a strategy to think about tests first.

- test name should be very descriptive. should state what test is expecting

- Arrange: organize the data needed to execute that piece of code (input);

- Act: execute the code being tested (exercise the behaviour);

- Assert: after executing the code, check if the result (output) is the same as you were expecting.

- **the cycle.**

- write a test and make it fail.
- write the feature and make it pass.
- refactor code.

## recursion
- The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function.

- How a particular problem is solved using recursion? 

- The idea is to represent a problem in terms of one or more smaller problems, and add one or more base conditions that stop the recursion. For example, we compute factorial n if we know factorial of (n-1). The base case for factorial would be n = 0. We return 1 when n = 0.

- If the base case is not reached or not defined, then the stack overflow problem may arise.