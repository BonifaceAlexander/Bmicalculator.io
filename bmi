# Get Height
from logging import raiseExceptions
from xdrlib import raise_conversion_error

height=float(input("Enter  your height in meter: ")or 0.0)
if(height <= 0):
    raise Exception("Please enter valid height only")
# Get Weight
weight=float(input("Enter your weight in kg: ")or 0)
if(weight <= 0):
    raise Exception(" Please enter valid weight only")
# calculate bmi
bmi= float(weight/(height ** 2))
print("Your bmi is:",round(bmi,2))

if(bmi <= 24.9 and bmi >= 18.5):
    print("You are in the Healthy weight")
elif(bmi < 18.5):
    print("You are Underweight")
elif(bmi <= 29.9 and bmi >= 25):
    print("You are Overweight")
else:
    print("You are Obesity")
