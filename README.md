# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept

## Equipment’s required:
PC
Anaconda - Python 3.7

## Algorithm: 
### Step 1: 
Commence the program 

### Step 2: 
Get the value from the user for the number of rotation

### Step 3: 
Using the slicing concept rotate the list

### Step 4: 
Print the rotated list

### Step 5: 
End the program

## Program:
```python

#Program to circulate N values.
#Developed by: PRAVEEN D
#RegisterNumber: 212222240076
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are:",a)
```    
## Output:
![output](output1.png)

## Result:
thus the circulating the values of N_variables are successfully executed
