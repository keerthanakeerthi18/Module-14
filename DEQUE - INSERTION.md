# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```
#Reg.no: 212222060119
#Name: KEERTHANA P
import collections
a=int(input())
b=int(input())
c=int(input())
d=collections.deque([a,b,c])
d.append(14)
d.append(15)
print("The deque after appending at right is : ")
print(d)

```

### OUTPUT
<img width="929" height="262" alt="image" src="https://github.com/user-attachments/assets/92f8ff7d-5ee9-4819-bebc-a488cb204ce5" />

### RESULT
Thus the python program is initialised and executed successfully.
