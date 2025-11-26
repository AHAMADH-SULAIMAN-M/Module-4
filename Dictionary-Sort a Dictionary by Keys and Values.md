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
```python
dct = {'b': 5, 'a': 2, 'd': 8, 'c': 1}

sorted_by_keys = dict(sorted(dct.items()))

sorted_by_values = dict(sorted(dct.items(), key=lambda item: item[1]))


print("Original dictionary:", dct)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```

## Sample Output


<img width="831" height="265" alt="image" src="https://github.com/user-attachments/assets/d9c34b0a-2653-4f7b-adf3-b89e97fc731d" />

## Result
The python program to sort the dict by key and values executed successfully and verfied.
