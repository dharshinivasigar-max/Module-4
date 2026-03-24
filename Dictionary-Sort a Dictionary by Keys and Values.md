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
my_dict = {
    "Zebra": "Black",
    "Apple": "Red",
    "Monkey": "Brown",
    "Banana": "Yellow",
    "Ocean": "Blue"
}

print("--- Original Dictionary ---")
print(my_dict)
print()

sorted_by_key = dict(sorted(my_dict.items()))

sorted_by_value = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("--- Sorted by Keys (Alphabetical) ---")
print(sorted_by_key)
print()

print("--- Sorted by Values (Alphabetical) ---")
print(sorted_by_value)
```

## Sample Output
--- Original Dictionary ---
{'Zebra': 'Black', 'Apple': 'Red', 'Monkey': 'Brown', 'Banana': 'Yellow', 'Ocean': 'Blue'}

--- Sorted by Keys (Alphabetical) ---
{'Apple': 'Red', 'Banana': 'Yellow', 'Monkey': 'Brown', 'Ocean': 'Blue', 'Zebra': 'Black'}

--- Sorted by Values (Alphabetical) ---
{'Zebra': 'Black', 'Ocean': 'Blue', 'Monkey': 'Brown', 'Apple': 'Red', 'Banana': 'Yellow'}


## Result

The Python program to sort a dictionary by its keys and values in alphabetical order was written and executed successfully. The output confirms that the sorted() function, combined with lambda functions for value-based sorting, correctly organizes the dictionary data.
