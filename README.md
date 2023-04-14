# pwskillass1
ans 1 
Variable names should be written in lowercase letters.
If a variable name consists of more than one word, separate the words using underscores. For example, my_variable.
Do not use built-in keywords or function names as variable names.
Avoid using single-character variable names except for temporary variables.
Use descriptive names that convey the purpose of the variable.
Constants should be written in uppercase letters with underscores separating words. For example, MY_CONSTANT.
Use camel case only for class names.
Use the plural form for collection data types, such as lists or dictionaries. For example, users instead of user.
Use meaningful prefixes for variable names, such as is_ for boolean values or num_ for numeric values.


ans 2
If you declare a restricted keyword as a variable in Python, you will get a SyntaxError. This is because keywords in Python are reserved for specific purposes and cannot be used as variable names. If you try to use a keyword as a variable name, Python will recognize it as a keyword and raise a syntax error.



ans 3
Yes, in Python, you can use a string as a variable name by enclosing the name in quotes. This technique is called dynamic variable naming or creating variables dynamically.



ans 4
Yes, in Python, it is possible to declare a variable with a single underscore _ as its name. However, the single underscore variable has a special meaning in Python, and it is commonly used as a placeholder variable.
In Python, the single underscore variable is used to represent the result of the last expression in the interpreter. It is also used as a placeholder variable for unused variables, to indicate that the value is not important or unused.
example
# Using a string to create a variable
variable_name = "my_variable"
value = 10
globals()[variable_name] = value

print(my_variable) # Output: 10




ans 4
In Python, variables are dynamic in nature, which means that their type can change during runtime, and they can be re-assigned to a value of a different type. This is different from statically typed languages like C or Java, where variables must be declared with a specific type and cannot change type during runtime.

Here's an example that demonstrates how variables in Python are dynamic in nature:


# Dynamic variables in Python
x = 10
print(x) # Output: 10

x = "hello"
print(x) # Output: hello

x = [1, 2, 3]
print(x)
