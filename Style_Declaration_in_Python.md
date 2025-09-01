# 🐍 Python Naming Conventions (PEP 8)

Quick reference for Python style rules when declaring variables, classes, methods, and constants.

---

## ✅ Summary

| Style                  | Example           | Usage in Python |
|-------------------------|------------------|-----------------|
| **snake_case**          | `user_name`      | ✅ Variables, functions, methods |
| **camelCase**           | `userName`       | ❌ Avoid (valid but un-Pythonic) |
| **PascalCase (CapWords)** | `UserName`    | ⚠️ Classes only |
| **UPPER_CASE**          | `MAX_LIMIT`      | ✅ Constants |
| **_underscore**         | `_hidden_value`  | ⚠️ Internal/private convention |
| **__double_underscore** | `__balance`      | ⚠️ Name mangling (private in classes) |
| **dunder**              | `__init__`       | ✅ Reserved for special methods |

---

## 📌 Examples

```python
# ✅ Variables & functions → snake_case
user_name = "Shashi"
max_connections = 10
def calculate_area(radius):
    return 3.14 * radius ** 2

# ✅ Constants → UPPER_CASE
PI = 3.14159
MAX_USERS = 100

# ✅ Classes → PascalCase
class UserAccount:
    pass

# ⚠️ Private (by convention) → _underscore
_hidden_value = 42

# ⚠️ Name Mangling → __double_underscore
class BankAccount:
    def __init__(self):
        self.__balance = 1000

acc = BankAccount()
# print(acc.__balance) ❌ AttributeError
print(acc._BankAccount__balance)  # ✅ Name mangling access

# ✅ Special Methods (Dunder)
class Person:
    def __init__(self, name):   # constructor
        self.name = name
    def __str__(self):          # string representation
        return f"Person: {self.name}"
