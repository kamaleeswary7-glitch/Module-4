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
```
data = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

sorted_keys = sorted(data.keys())
sorted_values = sorted(data.values())

print("Keys in alphabetical order:", sorted_keys)
print("Values in alphabetical order:", sorted_values)
```
## Sample Output
```
Keys in alphabetical order: ['a', 'b', 'c']
Values in alphabetical order: ['apple', 'banana', 'cherry']
```
## Result
the output is verified

