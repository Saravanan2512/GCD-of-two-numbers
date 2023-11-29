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
/*
Program to find the gcd of two number using function.
Developed by:SARAVANAN
RegisterNumber: 23005445
*/

n1=int(input())
n2=int(input())
def gcd():
    if n1<n2:
       smaller=n1
    else:
       smaller=n2
    for i in range(1,smaller+1):
          if n1%i==0 and n2%i==0:
              gcd=i
    print("GCD of two numbers is:",gcd)

```

## Output:
![gcd of two number](/Screenshot%20(66).png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
