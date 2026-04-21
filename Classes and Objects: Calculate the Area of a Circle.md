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

Add code here
import math

# Define class
class cse:
    # Define method to calculate area
    def mech(self, radius):
        return math.pi * radius * radius

# Driver code
r = float(input("Enter the radius of the circle: "))
obj = cse()
area = obj.mech(r)
print("Area of the circle:", area)


## Output
<img width="1012" height="640" alt="image" src="https://github.com/user-attachments/assets/3c8b9372-eecd-4871-99ef-712f5205483a" />


## Result
