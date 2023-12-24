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
i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Gnanendran N
RegisterNumber: 23006661
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

## Output:
![3a1](https://github.com/GnanendranN/FindMaximum/assets/138955207/b72dd987-6f0d-428a-ae5e-59f2b275777b)

![3a2](https://github.com/GnanendranN/FindMaximum/assets/138955207/6486da20-0139-42d0-b994-92b56e34fd9f)

![3a3](https://github.com/GnanendranN/FindMaximum/assets/138955207/f42453c5-5ec9-473f-90cd-7b6c917ccd71)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
