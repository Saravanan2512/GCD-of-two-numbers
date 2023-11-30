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
"""
program to find the gcd of two number using function. 
Developed by :SARAVANAN G
RegisterNumber:23005445
"""
def gcd():
    a=int(input())
    b=int(input())
    while b:
        a,b=b,a%b
    print(f"GCD of two numbers is:",a)

```

## Output:
![image](https://github.com/Saravanan2512/GCD-of-two-numbers/assets/144979117/00555904-e374-4620-8207-6214dbe07708)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
