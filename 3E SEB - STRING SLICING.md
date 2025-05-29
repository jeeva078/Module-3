# Exp.No:3e
## SEB - PYTHON FUNCTION TO CONVERT STRING TO TUPLE AND REMOVE 3RD ELEMENT

---

### AIM  
To write a Python function that accepts a string, converts it into a tuple, removes the 3rd element (index 2), and prints the original and modified tuples along with the removed character.


### ALGORITHM

Start

Define a function strtotuple(a) that accepts a string as input

Convert the string into a list using list(a)

Convert the list into a tuple and store it in a variable t

Create a new tuple r that excludes the 3rd element (index 2) using slicing: t[:2] + t[3:]

Print the original tuple t

Print the new tuple r after removal

Print the character that was removed (element at index 2)

End



---

### PROGRAM

```
def strtotuple(a):
    l = list(a)
    t = tuple(l)
    r = t[:2] + t[3:]
    print(t)
    print(r)
    print("Character Removed: {}".format(l[2]))

```

### OUTPUT
![Screenshot (237)](https://github.com/user-attachments/assets/07e5a5e7-44a2-4fe5-9d2b-55b2d871f46b)


### RESULT
Thus the python program was initiated and executed successfully.
