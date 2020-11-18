# global and nonlocal

## global 

- with a global statement you can define a list of names that are going to be treated as global names.

- The statement consists of the global keyword followed by one or more names separated by commas.

- **The use of global is considered bad practice in general** If you find yourself using global to fix problems like the one above, then stop and think if there is a better way to write your code.

- instead of using global you can return the result.

instead of
- counter = 0 
- def update_counter():
- `global counter`
- `counter =+ 1`

- you can use 
- `def update_counter():`
- `return counter + 1`

## nonlocal
- The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function.
- Use the keyword nonlocal to declare that the variable is not local.