# Exp.No:3c
## LIST -PYTHON PROGRAM TO REVERSE ELEMENTS OF A LIST

---

### AIM  
To write a Python program that reverses the elements of a given list using a loop and without using the built-in reverse functions.

---

### ALGORITHM

Start

Define a list called input_list with the given elements
Example: [1, 3, 5, 7, 9, 11, 13, 17, 19]

Calculate the length of the list using len(input_list) and store it in a variable n

Use a for loop to iterate from 0 to n//2:

Swap the element at index i with the element at index n - i - 1 using a temporary variable

After the loop ends, print the reversed list

End

---

### PROGRAM

```
input_list=[1,3,5,7,9,11,13,17,19]
n=len(input_list)
#for i in range(0,n):
 #   input_list.append(int(input()))
for i in range (n//2):
    temp=input_list[i]
    input_list[i]=input_list[n-i-1]
    input_list[n-i-1]=temp
print(input_list)

```

### OUTPUT
![Screenshot (235)](https://github.com/user-attachments/assets/473f50b4-aa95-4768-aae1-965bb60f9629)

### RESULT
Thus the python program was initiated and executed successfully.
