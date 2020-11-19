# dunder/magic methods

- Dunder methods let you emulate the behavior of built-in types. For example, to get the length of a string you can call len('string').

- Object Initialization: __init__
- __init__ is the object constructor of a class.

- Object Representation: __str__, __repr__
- in python it is common practice in python to provide a string representation of your object for the consumer of your class.

- __repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous.

- __str__: The “informal” or nicely printable string representation of an object. This is for the enduser

-  If you don’t want to hardcode "Account" as the name for the class you can also use self.__class__.__name__ to access it programmatically.

- Iteration: __len__, __getitem__, __reversed__
- makes objects iterable

- Context Manager Support and the With Statement: __enter__, __exit__
- A context manager is a simple “protocol” (or interface) that your object needs to follow so it can be used with the with statement.

- you need __ enter__ and __ exit__ methods into an ovject if you want it to function as a context manager.
