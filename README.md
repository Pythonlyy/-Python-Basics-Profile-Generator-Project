# 🐍 Python Basics: Profile Generator Project

Welcome to your **first Python project**! This beginner-friendly script teaches you the basics of Python by building a fun and simple **Profile Generator**. You’ll learn how to use variables, data types, print statements, and the `type()` function — the foundations of any Python program.

---

## 📌 What You'll Learn

* ✅ Python syntax basics
* ✅ Declaring and using variables
* ✅ Understanding data types (string, integer, float, boolean)
* ✅ Using the `print()` function
* ✅ Using the `type()` function to inspect data types
* ✅ Formatting output with f-strings

---

## 🧐 About the Project

This project builds a **fake profile generator** using hardcoded variables. Each variable represents a piece of user data like name, age, and favorite number. You'll then print those variables in a readable format and inspect their types.

This is an excellent **first project** to understand how Python thinks, stores, and prints information.

---

## 🧱 Project Code

```python
# Meet the Python Profile Generator 🧠🐍

# Step 1: Define variables
name = "Alice"                     # String
age = 25                           # Integer
favorite_number = 3.14            # Float
likes_python = True               # Boolean

# Step 2: Print basic profile info
print("👤 Name:", name)
print("🎂 Age:", age)
print("💯 Favorite Number:", favorite_number)
print("🐍 Likes Python?", likes_python)

# Step 3: Check data types
print("\n🔎 Let's check the data types!")
print("Type of name:", type(name))
print("Type of age:", type(age))
print("Type of favorite_number:", type(favorite_number))
print("Type of likes_python:", type(likes_python))

# Step 4: Combine all into one summary line
print(f"\n🧾 {name} is {age} years old, loves the number {favorite_number}, and it is {likes_python} that they like Python!")
```

---

## 🧪 Breakdown of Concepts

| Concept                  | Description                                     |
| ------------------------ | ----------------------------------------------- |
| `name = "Alice"`         | Stores a string value in a variable             |
| `age = 25`               | Stores an integer                               |
| `favorite_number = 3.14` | Stores a float (decimal number)                 |
| `likes_python = True`    | Stores a boolean (True/False)                   |
| `print()`                | Outputs information to the console              |
| `type()`                 | Shows the data type of a value                  |
| `f"{variable}"`          | Used in f-strings to insert variables into text |

---

## 🔧 How to Run This Project

1. Make sure you have **Python 3** installed.
2. Copy the code above into a file named `profile_generator.py`.
3. Open your terminal or command line.
4. Run the script:

   ```bash
   python profile_generator.py
   ```

---

## 🌱 Want to Make It Interactive?

Here’s a bonus challenge:

> Replace the hardcoded values with user input using the `input()` function.

```python
name = input("What's your name? ")
age = int(input("How old are you? "))
favorite_number = float(input("What's your favorite number? "))
likes_python = input("Do you like Python? (True/False): ") == "True"
```

---

🐍 This is part of the Pythonly beginner series.
Learn Python one line at a time. Follow @Pythonly for more.


