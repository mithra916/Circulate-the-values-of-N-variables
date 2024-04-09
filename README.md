# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Print both the values it would be interchanged
### Step 6:
End the program
## Program:
## DEVELOPED BY : R.LOGA MITHRA
## REGISTER NUMBER :212223100027
```
def circulate():
    s=n%len(my_lst)
    return my_lst[s::] + my_lst[0:s]
my_lst=eval(input())
n=int(input())
print("After circulating the values are:",circulate())
```
## Output:
![output](/py%20exp%202.png)
## Result:
Thus the circulate of variables are successfully executed

