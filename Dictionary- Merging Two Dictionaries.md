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
dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'b': 200, 'd': 400}


def merge(d1, d2):

    merged_result = {**d1, **d2}
    return merged_result

result = merge(dict1, dict2)
print("Merged Dictionary:", result)
```
## Output
Merged Dictionary: {'a': 10, 'b': 200, 'c': 30, 'd': 400}

## Result
The Python program successfully merges two dictionaries. As specified in the algorithm, the value for the key 'b' from dict2 (200) overwrote the value from dict1 (20), demonstrating how the unpacking operator handles duplicate keys.
