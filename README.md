- 👋 Hi, I’m @ndumisoluthuli
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ndumisoluthuli/ndumisoluthuli is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


1. Functions
Lesson: Defining and Using Functions
A function is a reusable block of code that performs a specific task. Here's how to define and use one:

```python

# Function to add two numbers
def add_numbers(a, b):
    return a + b

# Call the function
result = add_numbers(5, 3)
print("Sum:", result)  # Output: Sum: 8
```

Exercise 1: Square of a Number
Write a function that takes a number as input and returns its square.

```python
def square(num):
    return num ** 2

print(square(4))  # Should print 16
```

Now try:

Test the function with different numbers.
Modify it to return the cube of the number instead.
Exercise 2: Even or Odd
Write a function that checks if a number is even or odd and prints the result.

```python
def check_even_odd(num):
    if num % 2 == 0:
        print(f"{num} is even.")
    else:
        print(f"{num} is odd.")

check_even_odd(7)  # Should print "7 is odd."
```

2. Basic Loops
Lesson: For Loop Basics
A for loop is used to iterate over a sequence like a list, string, or range.

```python
# Example: Print numbers 1 to 5
for i in range(1, 6):
    print(i)
```
Exercise 1: Even Numbers
Write a program that prints all even numbers from 1 to 20 using a loop.

```python
for i in range(1, 21):
    if i % 2 == 0:
        print(i)
```
Lesson: While Loop Basics
A while loop runs as long as a condition is True.

```python
# Example: Countdown
count = 5
while count > 0:
    print(count)
    count -= 1
```

Exercise 2: User Input Loop
Write a program that keeps asking for a word until the user types "exit".

```python
while True:
    word = input("Enter a word (type 'exit' to quit): ")
    if word.lower() == "exit":
        break
    print("You entered:", word)
```

Practice Challenge:
Combine Functions and Loops!
Write a function that prints all the multiples of a number up to a given limit.

Example:

```python
def print_multiples(number, limit):
    for i in range(1, limit + 1):
        print(number * i)

print_multiples(3, 5)  # Should print 3, 6, 9, 12, 15
```
