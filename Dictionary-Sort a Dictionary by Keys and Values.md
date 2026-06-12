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

## 🧪Program:
```python
d = {'c': 'cat', 'a': 'apple', 'b': 'ball'}

sorted_keys = dict(sorted(d.items()))
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original Dictionary:", d)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
```

## Output:
<img width="734" height="189" alt="image" src="https://github.com/user-attachments/assets/689c1da3-a7f7-4eab-a625-92ca9fc77843" />


## Result:
Thus,the program is executed successfully.

