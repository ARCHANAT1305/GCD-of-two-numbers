# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#Program to find the GCD of numbers
#Developed by : ARCHANA.T
#Register Number :212223240013
def find_gcd(a,b):
    while b:
        a,b=b,a%b
    return a    
def gcd():
    num1 = int(input())
    num2 = int(input())
    result=find_gcd(num1,num2)
    print(f"GCD of two numbers is: {result}")
```

## Output:


![gcd](https://github.com/ARCHANAT1305/GCD-of-two-numbers/assets/145975189/62324570-abbd-4843-b9a9-15e9785c7fbf)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
