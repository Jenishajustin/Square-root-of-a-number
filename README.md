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
```python
Program Developed by: JENISHA.J
RegisterNumber:  22002972

b=int(input())
def newton_method(n,no_of_iters=100):
    b=float(n)
    for i in range(no_of_iters):
        n=0.5*(n+b/n)
    return n
print("Square root of the number:",newton_method(b))
```

## Output:
![sqrt](https://user-images.githubusercontent.com/119405070/210387364-096f51d5-0ec9-41c1-81b2-d94beb7f0b00.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
