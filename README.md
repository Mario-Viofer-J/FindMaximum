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
#Program to mark the maximum of marks using the list method sort
#Developed by: MARIO VIOFER J
#Register Number: 21222310032
def max_marks(marks):
    marks.sort(reverse=True)
    return marks[0]


```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by: MARIO VIOFER J
#Register Number: 21222310032
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to find the maximum marks without using builtin functions
#Developed by: MARIO VIOFER J
#Register Number: 21222310032
def max_marks(marks):
    if len(marks) == 0:
        return None
    max_mark = marks[0] 
    for mark in marks[1:]:
        if mark > max_mark:
            max_mark = mark
    return max_mark


```



## Output:
![image](https://github.com/Mario-Viofer-J/FindMaximum/assets/144979232/9f4a8ccd-b806-4861-a3ae-b7568da0b160)

![image](https://github.com/Mario-Viofer-J/FindMaximum/assets/144979232/7ca5b97a-fc6d-4a4c-a581-8cf55e8406f0)

![Screenshot 2024-04-06 165732](https://github.com/Mario-Viofer-J/FindMaximum/assets/144979232/faa820c2-f58e-4d5e-890b-10a5d0a2c870)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
