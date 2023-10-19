# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatentation operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
#Program to circulate N values.
#Developed by: Mani Sri Latha.M
#RegisterNumber:23008627

def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)

## Output:
![](circulate.png)
## Result:
Thus the python program for Circulatte the vallues of n variable is executed successfully.