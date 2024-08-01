# pycodes
echo "# pycodes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/pratiksha259311/pycodes.git
git push -u origin main
 Variables and Data Types
name = "John"  # string
age = 30  # integer
is_active = True  # boolean

# Lists
fruits = ["apple", "banana", "cherry"]
print(len(fruits))  # Output: 3

# Functions
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")  # Output: Hello, Alice!

# Conditional Statement
if age >= 18:
    print("You're an adult.")
else:
    print("You're a minor.")

# Loops
for fruit in fruits:
    print(fruit)  # Output: apple, banana, cherry

# Lambda Function
double_numbers = lambda x: x * 2
numbers = [1, 2, 3]
print(list(map(double_numbers, numbers)))  # Output: [2, 4, 6]
