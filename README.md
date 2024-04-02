# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
### DEVELOPED BY : N.PRAVESH
### REGISTER NO : 212223230154

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maximum = 0
    for i in marks:
        if i>maximum:
            maximum = i
    return maximum
```



## Output:

i)	# To find the maximum of marks using the list method sort.

![Screenshot 2024-03-31 062059](https://github.com/NPravesh2005/FindMaximum/assets/164477756/4b291c33-30e9-450d-b1cb-9b7fe7b4a985)

ii)	# To find the maximum marks using the list method max().

![Screenshot 2024-03-31 062205](https://github.com/NPravesh2005/FindMaximum/assets/164477756/407dd227-4bb7-4a88-b7bd-9bc5bac1c847)

iii) # To find the maximum marks without using builtin functions.

![Screenshot 2024-03-31 062229](https://github.com/NPravesh2005/FindMaximum/assets/164477756/483f9a8a-3003-43f4-9a75-dca4e399e618)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
