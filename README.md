# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```

Program to find the square root for the given number(newton's method) using function.
Developed by: SRINIDHI SENTHIL
RegisterNumber: 22001408

def sqrt():
    x=int(input())
    b=x
    for i in range(10):
        x=0.5*(x+b/x)
    return x
print("Square root of the number:",sqrt())
```

## Output:
![image](https://user-images.githubusercontent.com/121373170/212085605-46954f79-fcd5-4188-b8f3-744c9ef11911.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
