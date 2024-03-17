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
### Step 6: 
## Program:
```
def circulate():
    s=n%len(my_lst)
    return my_lst[s::] + my_lst[0:s]
my_lst=eval(input())
n=int(input())
print("After circulating the values are:",circulate())
```
## Output:
![img 1](https://github.com/mithra916/Circulate-the-values-of-N-variables/assets/149986612/2d0e24d8-f536-42e0-a97c-da7122aa6b58)

## Result:
