# 1. Variables in Python

Variables are one of the most fundamental concepts in any programming language. In Python, a variable is a name that refers to a value stored in memory. You can use variables to store and manipulate data throughout your code.

---

## 🧠 What is a Variable?

A variable:
- Has a **name** (identifier)
- Refers to a **value** in memory
- Can **change** or be **reassigned** later

Think of a variable as a labeled box where you store a value.

```python
age = 25
name = "Yunus"
height = 1.75
```

Here, `age`, `name`, and `height` are variables pointing to different types of values.

---

## 📝 Naming Rules

- Must start with a letter (a–z, A–Z) or underscore (_)
- Cannot start with a number
- Can include letters, numbers, and underscores
- Case-sensitive (`Name` and `name` are different)

✅ Valid:
```python
username = "john"
user_1 = 42
_name = "Mary"
```

❌ Invalid:
```python
1user = "nope"  # starts with a number
user-name = "error"  # hyphen not allowed
```

---

## 🔄 Variable Reassignment

Variables can be reassigned at any time:

```python
score = 10
score = 15  # now score is 15
```

---

## 📚 Variable Types

Python automatically detects the type of the variable:

```python
x = 10        # int
y = 3.14      # float
name = "Joseph"  # str
active = True # bool
```

You can check the type using `type()`:

```python
print(type(x))      # <class 'int'>
print(type(name))   # <class 'str'>
```

---

## 🧪 Quick Practice

```python
# Create variables for your name, age, and favorite language
my_name = "Yunus"
my_age = 41
fav_language = "Python"

print("Hi, my name is", my_name)
print("I am", my_age, "years old")
print("I love", fav_language)
```

---

## ✅ Summary

- Variables store data using a name
- They can be reassigned anytime
- Python infers the type based on the value
- Good variable names make your code readable

You're ready to start working with data in Python! 🐍
