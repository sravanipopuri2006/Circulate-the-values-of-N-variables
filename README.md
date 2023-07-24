# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function

### Step 2:
Get the list from the user 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the list
### Step 6:
Call the function 
## Program:
```
#Program to circulate N values.
#Developed by:Popuri Sravani 
#RegisterNumber:23006561
def circulate():
    list1=eval(input())
    a=int(input())
    list1=list1[a:]+list1[:a]
    print("After circulating the values are:",list1)
```
    
## Output:
![Alt text](/outputcirculate.png)

## Result:
Thus circulating n variables program has been executed  using function concept.


