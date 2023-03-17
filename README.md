# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Take input from the user for a list l.

### Step 2: 
Take input from the user for the number of positions to circulate n.

### Step 3: 
Using the slicing concept rotate the list

### Step 4: 
Print a message to the user saying "After circulating the values are:"

### Step 5: 
Print the new list (result) to the console.

### Step 6: 
End of the Program

## Program:

```
#Program to circulate N values.
#Developed by: HARISH RAGAV S
#RegisterNumber: 212222110013
def circulate():
   l = eval(input())
   n = int(input())
   result = l[n:] + l[:n]
   print("After circulating the values are:",result)
 ```


## Output:
![image](https://user-images.githubusercontent.com/119345345/225814637-0206c77d-cf17-4a0e-a6cf-9e54d71b4f43.png)


## Result:
Thus the program  to circulate the values of n variables are successfully executed
