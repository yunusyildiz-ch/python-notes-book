# 2. Data Types in Python

In Python, **data types** determine what kind of value a variable holds. Understanding data types is essential because they define how data behaves and how you can interact with it.

---

## 🔢 Basic Data Types

| Type      | Description                     | Example        |
|-----------|---------------------------------|----------------|
| `int`     | Integer (whole number)          | `x = 10`       |
| `float`   | Decimal number                  | `pi = 3.14`    |
| `str`     | String (text)                   | `name = "Yunus"` |
| `bool`    | Boolean (True or False)         | `is_active = True` |

---

## 🧠 Examples

```python
age = 30                  # int
price = 19.99            # float
first_name = "Yunus"      # str
is_logged_in = False     # bool
```

---

## 📏 Checking Types

You can use the `type()` function to check the type of a value:

```python
print(type(age))         # <class 'int'>
print(type(price))       # <class 'float'>
print(type(first_name))  # <class 'str'>
print(type(is_logged_in)) # <class 'bool'>
```

---

## 🔁 Type Conversion (Casting)

You can convert values from one type to another:

```python
x = 5          # int
x_str = str(x) # "5"

price = "19.99"
price_float = float(price)
```

Built-in functions:
- `int()` → to integer
- `float()` → to float
- `str()` → to string
- `bool()` → to boolean

---

## 🧪 Practice: Type Checking & Conversion

```python
user_input = "42"
number = int(user_input)

print("Value:", number)
print("Type:", type(number))
```

---

## ⚠️ Common Pitfalls

```python
x = "5"
y = 2
result = x + y  # ❌ TypeError: cannot concatenate str and int
```

✅ Fix:
```python
result = int(x) + y
```

---

## ✅ Summary

- Python has dynamic typing: variables can hold different types
- Use `type()` to inspect data types
- Use casting functions to convert between types
- Common types: `int`, `float`, `str`, `bool`

Understanding data types is crucial for writing bug-free, efficient Python code. 🧠🐍