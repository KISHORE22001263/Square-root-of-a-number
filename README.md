# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## STEP1  
Define a function.  
## STEP2  
Assign number_iters = 100 in the function to perform 100 iteratios.  
## STEP3    
Set i = 0.  
## STEP4  
Calculate  number = 0.5 * (number + a / number) for 100 iterations.  
## STEP5  
Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: KISHORE.B
RegisterNumber: 212222110020
def sqrt():
    num1=int(input())
    num2=float(num1)
    for i in range(100):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
sqrt()
```

## Output:
![Screenshot 2023-04-27 140451](https://user-images.githubusercontent.com/121484538/234806942-fdb15e07-9136-4eda-ad68-43f95ada5ca3.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
