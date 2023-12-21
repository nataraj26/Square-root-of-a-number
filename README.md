# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step 1
Define a function.
## step 2
Assign number_iters = 100 in the function to perform 100 iteratios.
## step 3
Set i = 0.
## step 4
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## step 5
Return number

## Program:
~~~python
Program to find the square root for the given number(newton's method) using function.
Developed by: NATARAJ KUMARAN S
RegisterNumber:  23003973
n=int(input())
app=0.5*n
for i in range (1,10):
    b=0.5*(app+n/app)
    app=b
print("Square root of the number:",b)
~~~

## Output:
![image](https://github.com/nataraj26/Square-root-of-a-number/assets/147514615/c5e971d8-afe1-423f-85ca-d255c8b879ca)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
