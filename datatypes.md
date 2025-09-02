# Python Built-in Data Types Examples

# Integers
```
big = 99999999999999999999999999
print(big * big)

a = 10
b = -5
c = 0

print(a + b)
print(a ** 3)
print(a // 3)

print(5 & 3)
```
# Floats
```
a = 3.193
b = -2

print(a + b)
print(type(a))
print(type(b))
```
# Lists
```
* Lists are ordered, mutable collections that can hold mixed types.
* They are one of the most flexible and commonly used data types in Python.
* Ordered and changeable
* Can contain duplicates
* Supports indexing, slicing, and nested lists

fruits = ["apple", "grapes", "banana", "cherry"]
print(fruits)

# Inserting an element
fruits[1] = 'orange'
print(fruits)

# Slicing the list
print(fruits[0::3])
print(fruits[::-1])

# List of Matrix
matrix = [[1, 2], [3, 4]]
print(matrix[1][0])

# Copying and refering diff
a = [1, 2, 3]
b = a // using the same memory 
c = a[:] //copying into the new list
b[0] = 100
print(b)
print(c)

# Append and Insert diff
nums = [5, 2, 9, 1]
nums.append(7)
nums.insert(2, 4)
print(nums)
nums.sort()
print(nums)

fruits = ["apple", "banana", "cherry"]
numbers = [10, 20, 30, 40]

print(fruits)
print(numbers)

fruits[1]='orange' # adds the element and the index 1.
print(fruits)

fruits.append('mangoes') # adds the element at the end of the list
print(fruits)


fruits.remove('orange') # it can remove the desired one
print(fruits)

pop_element=fruits.pop() #it removes last element
print(fruits)

# Nested lists
matrix = [[1,2,3],[4,5,6],[7,8,9]]
print(matrix[0][2])  # 3
print(matrix[2][1])  # 8

# List comprehension
squares=[ i**2 for i in range(5)]
print(squares) # [0, 1, 4, 9, 16]

fruits = ["apple", "banana", "cherry"]
numbers = [10, 20, 30, 40]

print("apple" in fruits)  # True
print(50 in numbers)

for fruit in fruits:
    print(fruit.upper())

## Adding the additional string to existing variable.
combined = fruits + ["mango", "pineapple"]
print(combined)
```
# Tuple
```
Tuple is a immutable order of collection in Python.
```
**Eg:**
```
my_tuple = (10, 20, 30, "hello", True)
print(my_tuple)
```
