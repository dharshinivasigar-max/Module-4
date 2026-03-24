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
```
list1 = [10, 20, 30, 40, 50]

try:
    # Attempt to access an index that is out of range
    # list1 has 5 elements (indices 0 to 4), so index 5 is out of range
    print("Accessing element at index 5...")
    element = list1[5]
    print("Element found:", element)

except IndexError:
    # 3. Catch the error and print a custom message
    print("You're out of list range")


print("Program execution continues...")
```
## Output
Accessing element at index 5...
You're out of list range
Program execution continues...


## Result
The program successfully demonstrates Exception Handling in Python. By using a try-except block, the code prevents the program from crashing when an IndexError occurs. Instead of a fatal error, it catches the exception and displays the custom message: "You're out of list range".

