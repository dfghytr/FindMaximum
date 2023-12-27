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
Program to mark the maximum of marks using the list method sort
Developed by: k M ABDUL KALAAM
RegisterNumber: 23005114
'''
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: k M ABDUL KALAAM
RegisterNumber: 23005114
'''
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: k M ABDUL KALAAM
RegisterNumber:23005114 
'''
def max_marks(list1):
    for i in list1:
        if i>94:
            return i


```

## Output:
![Screenshot 2023-12-27 154031](https://github.com/dfghytr/FindMaximum/assets/138970628/b6c7996f-711f-462e-805d-2a720b6139e9)

![Screenshot 2023-12-27 154044](https://github.com/dfghytr/FindMaximum/assets/138970628/5d5337c2-7c27-4754-b13c-020964f7a23e)


![Screenshot 2023-12-27 154055](https://github.com/dfghytr/FindMaximum/assets/138970628/164c0fde-7c40-417f-8d29-8ceef61de5e1)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
