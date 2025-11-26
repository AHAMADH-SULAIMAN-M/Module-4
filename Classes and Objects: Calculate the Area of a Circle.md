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
```python

import math

class cse:
    def mech(self,radius):
        print("Area of the Circle:",(math.pi * (radius **2)))
        
radius = int(input())
obj = cse()
result = obj.mech(radius)

```

## Output

<img width="814" height="244" alt="image" src="https://github.com/user-attachments/assets/eda7439e-a9cc-47cf-b3c3-b8ea2c6ae187" />

## Result
The python program to calculate area of the circle based in the radius provided by the user is executed successfully and verified
