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
```py
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Arshatha P
RegisterNumber: 22009104
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```py
Program to find the maximum marks using the list method max().
Developed by: Arshatha P
RegisterNumber:22009104
'''
def max_marks(marks):
    la=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```py
Program to the maximum marks without using builtin functions.
Developed by: Arshatha P
RegisterNumber:22009104
''' 
Program to the maximum marks without using builtin functions.
Developed by: Arshatha P
RegisterNumber: 22009104
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i 
    return max
```
## Sample Input and Output
![output](./11.png) 
![out](/12.png)
![out](/13.png)

## Output:
![output](./ans%201.png)
![output](./ans%202.png)
![output](/ans%203.png)







    
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
