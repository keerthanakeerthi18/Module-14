# Exp No: 36  
## Circular Queue 
---

### AIM  
To write a Python program with a function to insert float values into a Circular Queue.

---

### ALGORITHM

1. Start  
2. Check if the Circular Queue is full  
   - If `size == max_size`, print `"Queue is full"` and exit the function  
3. If the queue is not full:  
   - Read the element to be inserted  
   - Convert it to float  
   - Insert the element at the `tail` position  
   - Update tail using: `tail = (tail + 1) % max_size` (circular increment)  
   - Increment `size` by 1  
4. End

---

### PROGRAM

```
#Reg.no: 212222060119
#Name: KEERTHANA P
# Queue simply works in FIFO
class queue:
    def __init__(self, size):
        self.size=size
        self.queue=[]
        self.front=0
        self.rear=0

    def enqueue(self, item):
        if len(self.queue)==self.size:
            print("Queue is full")
            return
        else:
            self.queue.insert(self.rear,item)
            self.rear+=1
            
    def dequeue(self):
        if self.front==self.rear:
            print("queue is underflow")
        else:
            self.queue.pop(self.front)
            self.front+=1
        
   

    def display(self):
       print(self.queue)
       

a = int(input())
q = queue(a)
q.enqueue(float(input()))
q.enqueue(float(input()))
q.enqueue(float(input()))
q.display()

```

### OUTPUT
<img width="612" height="324" alt="image" src="https://github.com/user-attachments/assets/46481590-ea30-4214-89fc-6889792d7ac5" />

### RESULT
Thus the python program was initiated and executed successfully.
