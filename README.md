# To-study-Arithmetic-Relational-and-Logical-Operators-and-Operands-in-python
Assignment NO :2 1. WAP to add two numbers in python 2. WAP to declare variables and display types of respective
# Program to add two numbers

num1 = 10
num2 = 20

sum = num1 + num2

print("First Number:", num1)
print("Second Number:", num2)
print("Sum =", sum)
 variables 3. WAP to demonstrate type casting in python 4. WAP to demonstrate Logical operators

OUTPUT 
First Number: 10
Second Number: 20
Sum = 30

# Program to declare variables and display their types

integer_value = 10
float_value = 10.5
string_value = "Shravani"
boolean_value = True

print("Integer value:", integer_value, "Type:", type(integer_value))
print("Float value:", float_value, "Type:", type(float_value))
print("String value:", string_value, "Type:", type(string_value))
print("Boolean value:", boolean_value, "Type:", type(boolean_value))

OUTPUT 
Integer value: 10 Type: <class 'int'>
Float value: 10.5 Type: <class 'float'>
String value: Shravani Type: <class 'str'>
Boolean value: True Type: <class 'bool'>

# Program to demonstrate type casting

a = 10        # integer
b = 5.5       # float

print("Original value of a:", a, "Type:", type(a))
print("Original value of b:", b, "Type:", type(b))

# Type casting
a = float(a)
b = int(b)

print("After type casting a:", a, "Type:", type(a))
print("After type casting b:", b, "Type:", type(b))

 OUTPUT 
Original value of a: 10 Type: <class 'int'>
Original value of b: 5.5 Type: <class 'float'>
After type casting a: 10.0 Type: <class 'float'>
After type casting b: 5 Type: <class 'int'>

# Program to demonstrate logical operators

a = True
b = False

print("Value of a:", a)
print("Value of b:", b)

print("a AND b:", a and b)
print("a OR b:", a or b)
print("NOT a:", not a)
print("NOT b:", not b)

OUTPUT 
Value of a: True
Value of b: False
a AND b: False
a OR b: True
NOT a: False
NOT b: True