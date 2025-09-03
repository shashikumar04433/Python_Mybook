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
sequence[start : stop : step]

eg:
a=[1,2,3,4,5,6]
print(a[0:3:1])

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


nums.insert(3,1000)
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
**List Real time questions**
```
## list realtime operations
## only add make a sum of from 44 to 78 add and give final value
a=[1,5,44,55,67,86,56,78,87,876]
b=a[2:8]
print(b)
print(sum(b))
```
```
#print alternative and then add them
a=[1,2,3,4,5,6,7,8,9]
b=a[1:8:2]
print(sum(b))
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
```
 ## value present or not
t = (10, 20, 30,5,70,60,40)
print(60 in t) #False
print(30 in t) # True
print(len(t))
print(t.index(20))
print(t.count(20))


## 1 is in 0 index,(2,3,4) is in 1 index and (6,7,8) in second index
a=(1,(2,3,4),(6,7,8))
print(a[2][2]) # output 8

## inbuilt functions with Tuples
print(min(t))
print(max(t))
print(sum(t))
print(type(t))
print(sorted(t))

## min number find without in-build

a=(9,5,6,4,66,77,4)

min_number=a[0]

for i in a:
    if i < min_number:
        min_number=i
print(min_number)

## max number find without in-build
a=(9,5,6,4,66,77,4)

min_number=a[0]

for i in a:
    if i > min_number:
        min_number=i
print(min_number)
```
