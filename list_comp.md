# list comprehension in Python

- list comprhensions provide a way to create lists.

- It consists of brackets containing an expression followed by a for clause.

- `new_list = []`
- `for i in old_list:`
-    `if filter(i):`
-    `new_list.append(expressions(i))`

- this ^ becomes....

- `new_list = [expression(i) for i in old_list if filter(i)]`

- new_list
The new list (result).

- expression(i)
Expression is based on the variable used for each element in the old list.

- for i in old_list
The word for followed by the variable name to use, followed by the word in the
old list.

- if filter(i)
Apply a filter with an If-statement.