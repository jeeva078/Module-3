# Exp.No:3a
## STRING - PYTHON PROGRAM TO PARTITION A STRING AT THE WORD 'WORK'



---

### AIM  
To write a Python function that accepts a string and partitions it into three parts at the first occurrence of the word "work" using the partition() method.

---

### ALGORITHM

Start

Define a function named part that takes a string as input

Use the built-in partition() method on the string with 'work' as the separator

The partition() method will return a tuple with three parts:

The part before 'work'

The word 'work'

The part after 'work'

Return or print the resulting tuple

End

---

### PROGRAM

```
def part(input_string):
    string = input_string.split("work")
    result = (string[0], "work", string[1]) if len(string) > 1 else (string)
    print(result)
```

### OUTPUT
![Screenshot (233)](https://github.com/user-attachments/assets/ecd62d31-c467-4af1-8271-ed3de30cec4b)

### RESULT
Thus the python program was initiated and executed successfully.
