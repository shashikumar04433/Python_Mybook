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
fruits = ["apple", "grapes", "banana", "cherry"]
print(fruits)

fruits[1] = 'orange'
print(fruits)

print(fruits[0::3])
print(fruits[::-1])

matrix = [[1, 2], [3, 4]]
print(matrix[1][0])

a = [1, 2, 3]
b = a
c = a[:]
b[0] = 100
print(b)
print(c)

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

```
