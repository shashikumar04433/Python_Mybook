# Python Built-in Data Types Examples

This README demonstrates examples of Python’s built-in data types: **int**, **float**, **list**, and **tuple**, along with their usage and purpose.

---

## 🔢 Integers (`int`)

Integers represent **whole numbers** (positive, negative, or zero).  
They support arithmetic operations, bitwise operations, and have **no size limit** in Python.

```python
big = 99999999999999999999999999
print(big * big)  # works fine (no overflow in Python)

a = 10        # positive int
b = -5        # negative int
c = 0         # zero

# Arithmetic
print(a + b)      # 5
print(a ** 3)     # 1000 (power)
print(a // 3)     # 3 (floor division)

# Bitwise
print(5 & 3)      # 1 (binary AND: 101 & 011 = 001)

```
2.Float
a = 3.193
b = -2

print(a + b)       # 1.193
print(type(a))     # <class 'float'>
print(type(b))     # <class 'int'>
