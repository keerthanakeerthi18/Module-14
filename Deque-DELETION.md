# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
#Reg.no: 212222060119
#Name: KEERTHANA P
import collections
a=input()
b=input()
c=input()
de=collections.deque([a,b,c])
de.popleft()
print("The deque after deletion is :")
print(de)
```

### OUTPUT
<img width="847" height="270" alt="image" src="https://github.com/user-attachments/assets/eea47afb-17d1-4ee5-8e2c-f33b16b06ecf" />


### RESULT
Thus the python program is initialised and executed successfully.
