<!-- 1. False
Definition: A Boolean value representing false.
Use Case: Used in conditional statements or as part of logical operations.
Example: -->
    is_active = False
    if not is_active:
        print("The user is inactive.")
        
<!-- 2. None
Definition: Represents the absence of a value.
Use Case: Used to signify "no value" or "null" in Python.
Example: -->
    result = None
    if result is None:
        print("No result available.")
        
<!-- 3. True
Definition: A Boolean value representing true.
Use Case: Used in conditional expressions or logical operations.
Example: -->
    is_logged_in = True
    if is_logged_in:
        print("Welcome back!")
        
<!-- 4. and
Definition: A logical operator that returns True if both operands are True.
Use Case: Used to combine conditional statements.
Example: -->
    a = True
    b = False
    if a and b:
        print("Both are true.")
    else:
        print("One or both are false.")
        
<!-- 5. as
Definition: Used to create an alias for a module or exception handling.
Use Case: Commonly used in import statements and exception handling.
Example: -->
    import math as m
    print(m.sqrt(16))  # Aliased math as 'm'
    
<!-- 6. assert
Definition: Used for debugging purposes. Tests if a condition is true; if not, it raises an AssertionError.
Use Case: Typically used to ensure assumptions made by the code hold true.
Example: -->
    x = 10
    assert x > 0, "x should be greater than 0"
    
<!-- 7. async
Definition: Declares an asynchronous function that can be paused and resumed.
Use Case: Used to define asynchronous functions for non-blocking execution.
Example: -->
    async def fetch_data():
        return "Data fetched"
        
<!-- 8. await
Definition: Pauses the execution of a coroutine until the awaited coroutine completes.
Use Case: Used within asynchronous functions.
Example: -->
    async def fetch_data():
        await some_async_function()
        
<!-- 9. break
Definition: Terminates the loop immediately.
Use Case: Used inside loops (for, while) to exit the loop based on a condition.
Example: -->
    for i in range(10):
        if i == 5:
            break
        print(i)
        
<!-- 10. class
Definition: Defines a new class.
Use Case: Used to create objects and define behavior.
Example: -->
    class Dog:
        def bark(self):
            print("Woof!")
    my_dog = Dog()
    my_dog.bark()

<!-- 11. continue
Definition: Skips the rest of the code inside the loop for the current iteration and moves to the next iteration.
Use Case: Used inside loops (for, while) to skip to the next iteration.
Example: -->
    for i in range(5):
        if i == 3:
            continue
        print(i)

<!-- 12. def
Definition: Defines a new function.
Use Case: Used to create user-defined functions.
Example: -->
    def greet(name):
        return f"Hello, {name}!"
    print(greet("Alice"))

<!-- 13. del
Definition: Deletes a reference to an object.
Use Case: Used to delete variables, list items, or object attributes.
Example: -->
    my_list = [1, 2, 3]
    del my_list[0]
    print(my_list)  # Output: [2, 3]

<!-- 14. elif
Definition: Used in conditional statements to define an additional condition if the previous condition is false.
Use Case: Allows multiple conditions to be tested in sequence.
Example: -->
    x = 5
    if x > 10:
        print("x is greater than 10")
    elif x == 5:
        print("x is 5")

<!-- 15. else
Definition: Specifies a block of code to execute if the condition in an if or elif statement is false.
Use Case: Used with if and elif to handle cases when no condition is met.
Example: -->
    x = 2
    if x > 3:
        print("x is greater than 3")
    else:
        print("x is less than or equal to 3")

<!-- 16. except
Definition: Specifies a block of code to be executed if an error occurs in the try block.
Use Case: Used for handling exceptions in Python.
Example: -->
    try:
        result = 10 / 0
    except ZeroDivisionError:
        print("Error: Division by zero")

<!-- 17. finally
Definition: Specifies a block of code to be executed after a try block, regardless of whether an exception was raised.
Use Case: Ensures that some code runs no matter what happens inside the try block.
Example: -->
    try:
        result = 10 / 0
    except ZeroDivisionError:
        print("Error: Division by zero")
    finally:
        print("This block always runs")

<!-- 18. for
Definition: Used to create a loop that iterates over a sequence (like a list, tuple, or string).
Use Case: Repeats a block of code a specific number of times or over items in a sequence.
Example: -->
    for i in range(3):
        print(i)

<!-- 19. from
Definition: Used in import statements to import specific parts of a module.
Use Case: Allows for importing only certain functions or classes from a module.
Example: -->
    from math import sqrt
    print(sqrt(16))

<!-- 20. global
Definition: Declares that a variable is global and can be accessed or modified outside the current function.
Use Case: Used to modify a global variable inside a function.
Example: -->
    x = 10
    def update_x():
        global x
        x = 20
    update_x()
    print(x)  # Output: 20

<!-- 21. if
Definition: Used to start a conditional statement.
Use Case: Evaluates a condition and executes a block of code if the condition is true.
Example: -->
    x = 5
    if x > 3:
        print("x is greater than 3")

<!-- 22. import
Definition: Imports a module or package into the current namespace.
Use Case: Used to bring external modules into a script.
Example: -->
    import math
    print(math.pi)

<!-- 23. in
Definition: Used to check for membership in sequences (like strings, lists, etc.).
Use Case: Checks if an element exists in a collection.
Example: -->
    if "apple" in ["apple", "banana", "cherry"]:
        print("Apple is in the list.")

<!-- 24. is
Definition: Tests for object identity (whether two objects are the same instance in memory).
Use Case: Checks if two variables refer to the same object.
Example: -->
    a = [1, 2, 3]
    b = a
    print(a is b)  # True, both refer to the same object

<!-- 25. lambda
Definition: Creates an anonymous function.
Use Case: Used to create small, unnamed functions in one line.
Example: -->
    add = lambda x, y: x + y
    print(add(3, 4))  # Output: 7

<!-- 26. nonlocal
Definition: Declares a variable from an outer (enclosing) scope in a nested function.
Use Case: Used to modify a variable defined in the nearest enclosing scope.
Example: -->
    def outer_function():
        x = "outer"
        def inner_function():
            nonlocal x
            x = "inner"
        inner_function()
        print(x)
    outer_function()  # Output: inner

<!-- 27. not
Definition: A logical operator that returns True if the operand is False and vice versa.
Use Case: Used to negate a condition.
Example: -->
    a = False
    if not a:
        print("a is False")

<!-- 28. or
Definition: A logical operator that returns True if at least one of the operands is True.
Use Case: Combines multiple conditions in a logical expression.
Example: -->
    a = True
    b = False
    if a or b:
        print("At least one is true.")

<!-- 29. pass
Definition: A null statement that does nothing; it's a placeholder for future code.
Use Case: Used when a statement is required syntactically but you don’t want to execute any code.
Example: -->
    def function():
        pass  # Placeholder for future implementation

<!-- 30. raise
Definition: Used to raise an exception.
Use Case: Explicitly trigger an error or exception.
Example: -->
    def check_value(x):
        if x < 0:
            raise ValueError("x cannot be negative")
    check_value(-1)  # Raises a ValueError

<!-- 31. return
Definition: Exits a function and returns a value.
Use Case: Used to return a result from a function to the caller.
Example: -->
    def square(x):
        return x * x
    result = square(4)
    print(result)  # Output: 16

<!-- 32. try
Definition: Defines a block of code to be tested for errors.
Use Case: Used in conjunction with except and finally to handle exceptions.
Example: -->
    try:
        result = 10 / 0
    except ZeroDivisionError:
        print("Cannot divide by zero.")
<!-- 33. while
Definition: Creates a loop that continues as long as a condition is true.
Use Case: Used for repeating a block of code an unknown number of times until a condition changes.
Example: -->
    count = 0
    while count < 5:
        print(count)
        count += 1
<!-- 34. with
Definition: Used to wrap the execution of a block with methods defined by a context manager.
Use Case: Helps in resource management, such as opening files, by ensuring they are properly closed after use.
Example: -->
    with open('file.txt', 'r') as file:
        content = file.read()
<!-- 35 yield
Definition: Used to make a function generator, allowing it to return an iterator.
Use Case: Produces a sequence of values over time, instead of returning them all at once.
Example: -->
    def countdown(n):
        while n > 0:
            yield n
            n -= 1

    for number in countdown(5):
        print(number)
