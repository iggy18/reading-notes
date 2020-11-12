# classes and objects

- **Objects** are an encapsulation of variables and functions into a single entity.

- Classes are essentially a template to create your objects.

- To create a class, use the keyword `class:`
- `class classy:`
-   `x = 42`
- you can use the class named classy to create objects:
- `meaning = classy`
- `print(meaning.x)`
- All classes have a function called __init__(), which is always executed when the class is being initiated.

- Use the __init__() function to assign values to object properties, or other operations that are necessary to do when the object is being created:
- `class Person:`
    `def __init__(self, name, age):`
        `self.name = name`
        ` self.age = age`

- Objects can also contain *methods*. Methods in objects are functions that belong to the object and are in the class. 

- The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

## recursive thinking
-  A recursive function is a function defined in terms of itself via self-referential expressions.
-the function will continue to call itself and repeat its behavior until some condition is met to return a result.
- If the current problem represents a simple case, solve it. If not, divide it into subproblems and apply the same strategy to them.
-

 
- example: 
- `houses = ["Eric's house", "Kenny's house", "Kyle's house", "Stan's house"]`

- *Each function call represents an elf doing his work* 
- `def deliver_presents_recursively(houses):`
-    *worker elf doing his work*
-    `if len(houses) == 1:`
-    `house = houses[0]`
-    `print("Delivering presents to", house)`

-    *Manager elf doing his work*
-    `else:`
-   `mid = len(houses) // 2`
-    `first_half = houses[:mid]`
-    ` second_half = houses[mid:]`

-    *Divides his work among two elves*
-    `deliver_presents_recursively(first_half)`
-    `deliver_presents_recursively(second_half)`

## pytest.

- fixtures are objects that contain data shared between tests
- code coverage - there is a package called pytest-cov on pypi that you can download and install. you can invoke pytest with -- cov option.


