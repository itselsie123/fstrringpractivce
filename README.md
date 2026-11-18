# fstrringpractivce

name = input("What is your name? ")
favorite_food = input("What is your favorite food? ")

print()
print(f"Hello {name}! I hear you like {favorite_food}!")

# Ask the user for two numbers and convert them to integers
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

# Print a blank line to match the example output spacing
print()

# Display the results with calculations performed inside the curly braces
print(f"{num1} + {num2} = {num1 + num2}")
print(f"{num1} - {num2} = {num1 - num2}")
print(f"{num1} * {num2} = {num1 * num2}")
# 1. Create a variable containing your name in lowercase
my_name = "elsie thomas"

# 2. Use an f-string and .title() to display your name with capital letters
print(f"Title Case: {my_name.title()}")

# 3. Use another f-string and .upper() to display your name in all capital letters
print(f"Uppercase: {my_name.upper()}")
# 1. Create a variable containing a decimal number with at least five decimal places
decimal_num = 88.8888888

# 2. Use an f-string to display that number rounded to two decimal places
print(f"Original: {decimal_num}")
print(f"Formatted: {decimal_num:.2f}")

# 1. What does the f before a string tell Python to do?
# The 'f' creates a formatted string literal (f-string). It tells Python to
# evaluate any expressions inside curly braces {} and insert their values
# directly into the string.

# 2. What can you put inside the curly braces {} of an f-string? Give two examples.
# You can put any valid Python expression inside the curly braces, such as
# variables, math calculations, or function calls.
# Example 1 (Variable): f"Student name: {student_name}"
# Example 2 (Math expression): f"Next year you will be {age + 1} years old."
