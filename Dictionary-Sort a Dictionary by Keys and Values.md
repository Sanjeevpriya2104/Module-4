# 4(C) Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## Algorithm

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

## Program
```
d = {3: "apple", 1: "banana", 6: "grape", 5: "orange", 4: "mango", 2: "kiwi"}
print("Keys are")
for key in sorted(d.keys()):
    print(key, end=" ")
```

## Sample Output
<img width="379" height="156" alt="Screenshot 2025-11-25 204339" src="https://github.com/user-attachments/assets/0be008d2-244f-45f8-82b6-bc1a68e26d44" />


## Result
programme executed successfully
