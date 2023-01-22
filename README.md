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
#Developed by: sakthivel.R
#Register Number: 22009121
def gcd():
    n1,n2=int(input()),int(input())
    if n1<n2:
         smaller=n1
    else:
         smaller=n2
    for i in range (1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)``

```

## Output:

 
![Screenshot from 2023-01-11 23-05-23](https://user-images.githubusercontent.com/120550359/211877880-d3a4f412-eeb3-446d-86d2-c31b82885aa5.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
