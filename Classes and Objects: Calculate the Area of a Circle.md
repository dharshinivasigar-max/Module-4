# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    
    def mech(self, radius):
        area = math.pi * (radius ** 2)
        return area

r = float(input("Enter the radius of the circle: "))

obj = cse()

result = obj.mech(r)

print(f"The area of the circle with radius {r} is: {result:.2f}"
```
## Output
Enter the radius of the circle: 5
The area of the circle with radius 5.0 is: 78.54

## Result
The Python program successfully calculates the area of a circle using a class-based approach

