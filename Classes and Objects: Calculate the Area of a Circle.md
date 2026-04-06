# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
import math

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print(area)

r = float(input("Enter radius: "))

obj = cse()
obj.mech(r)
```
<img width="546" height="264" alt="image" src="https://github.com/user-attachments/assets/04606cd2-65f9-4796-8b8c-e51082590bf0" />

OUTPUT:


## Result
Thus the code ran successfully!

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
def merge(dict1, dict2):
    return {**dict1, **dict2}

dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

result = merge(dict1, dict2)

print(result)
```

## Output
<img width="502" height="141" alt="image" src="https://github.com/user-attachments/assets/77e18a1a-928a-44f2-90f7-d19347677ee4" />


## Result
Thsu the code ran successfully!

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
Add Code here
```
d = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

print("Original:", d)

# Sort by keys
sorted_keys = dict(sorted(d.items()))
print("Sorted by keys:", sorted_keys)

# Sort by values
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by values:", sorted_values)
```
## Sample Output
<img width="820" height="206" alt="image" src="https://github.com/user-attachments/assets/9ba97884-4088-4dc3-ba03-f4769ce81766" />


## Result
Thus the code run successfully!

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
Add code here
```
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="465" height="121" alt="image" src="https://github.com/user-attachments/assets/9e9e8077-d7e7-46c1-9889-6299e3b6c8bd" />


## Result
Thus the code run successfully!

