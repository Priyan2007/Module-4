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
