## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```python
# define two dictionaries
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

# function to merge
def merge():
    merged = {**dict1, **dict2}  
    return merged

# call the function and print
print("Merged dictionary:", merge())

```

## Output

<img width="823" height="195" alt="image" src="https://github.com/user-attachments/assets/d523734b-63bd-4f7a-b29f-e9df9176a026" />

## Result
The python program to merge two dictionaries and combines thier key value pairs is executed successfully and verified.
