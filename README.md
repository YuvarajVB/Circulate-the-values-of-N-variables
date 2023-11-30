# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the value from the user for the list using list1=eval(input()).

### Step 2: 
Get the value from the user for the number of rotations using n=int(input()).

### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
(Implicit) The slicing operation is the key concept used for circular shifting in this code

### Step 6: 
The program execution is complete. The resulting list after circular shift has been printed to the user.

## Program:
```
#Program to circulate N values.
#Developed by: YUVARAJ V
#RegisterNumber 23013769
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![output](/circulate.png)
## Result:
Thus the circulating n variables using function concept is successfully executed
