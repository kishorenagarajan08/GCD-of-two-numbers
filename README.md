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
#Program to find the gcd of a number using function
#Developed by:kishore N
#RegisterNumber:212223230106
def gcd():
    number1,number2=int(input()),int(input())
    if number1<number2:
        smaller=number1
    else:
        smaller=number2
    for i in range(1,smaller+1):
        if (number1%i==0 and number2%i==0):
            gcd1=i
    print("GCD of two numbers is:",gcd1)
/*
Program to find the gcd of two number using function.
Developed by: 
RegisterNumber:  
*/
```

## Output:
![Screenshot 2024-04-16 214538](https://github.com/kishorenagarajan08/GCD-of-two-numbers/assets/155753188/929763c2-061e-4604-8eff-a1617e4cc330)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
