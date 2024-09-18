### 1. Using the `format()` Method
The `format()` method is versatile and can insert variables into strings using curly braces `{}` as placeholders.

```python
name = "Mohsin"
age = 19

# Using the format() method
formatted_string = "My name is {} and I am {} years old.".format(name, age)
print(formatted_string)  # Output: My name is Mohsin and I am 19 years old.
```

### 2. Using f-Strings (Formatted String Literals) - Python 3.6+
f-Strings provide a more readable and concise way to format strings.

```python
name = "Mohsin"
age = 19

# Using f-strings
formatted_string = f"My name is {name} and I am {age} years old."
print(formatted_string)  # Output: My name is Mohsin and I am 19 years old.
```

### 3. Using `%` Operator (Old Style)
The `%` operator is an older way of formatting strings in Python.

```python
name = "Mohsin"
age = 19

# Using % operator
formatted_string = "My name is %s and I am %d years old." % (name, age)
print(formatted_string)  # Output: My name is Mohsin and I am 19 years old.
```

### 4. Using `str.format()` with Named Placeholders
You can also use named placeholders with the `format()` method for more clarity.

```python
formatted_string = "My name is {name} and I am {age} years old.".format(name="Mohsin", age=19)
print(formatted_string)  # Output: My name is Mohsin and I am 19 years old.
```

Each method has its use cases, but f-strings are generally the most preferred for their simplicity and readability.