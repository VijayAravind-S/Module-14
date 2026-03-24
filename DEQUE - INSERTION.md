# Exp.No:14c 
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
#Reg.No: 212222060292
#Name: Vijay Aravind S
#Add Your Code Here
import collections
a=input()
b=input()
c=input()
de=collections.deque([a,b,c])
de.append('h')
de.append('o')
de.append('n')
print("The deque after appending at right is :")
print(de)
```

### OUTPUT
<img width="1185" height="243" alt="image" src="https://github.com/user-attachments/assets/f440d580-38de-4623-bab6-b18a69b6870d" />

### RESULT
Therefore, the output is the example to write a Python program to insert elements at REAR END of deque using a collection built-in function.
