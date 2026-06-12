## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program:
```python
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge():
    merged = {**dict1, **dict2}
    print(merged)

merge()
```

## Output:
<img width="462" height="134" alt="image" src="https://github.com/user-attachments/assets/cb4561d6-8e99-414c-9d82-d5b26f2ef421" />


## Result:
Thus,the program is executed successfully.
