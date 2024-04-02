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
```
#Program to mark the maximum of marks using the list method sort.
#Program Developed by: S LALIT CHANDRAN
#Register No: 212223240077

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Program developed by: S LALIT CHANDRAN
#Register No: 212223240077

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
#Program to find the maximum marks without using builtin functions.
#Program developed by: S LALIT CHANDRAN
#Register No: 212223240077

def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark


```



## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2024-04-02 080142](https://github.com/lalitchandran/FindMaximum/assets/137707725/c6306be3-b5ff-4d96-94c3-dae8f3a3876b)


ii)	# To find the maximum marks using the list method max().
![Screenshot 2024-04-02 080158](https://github.com/lalitchandran/FindMaximum/assets/137707725/62d369f4-6271-48d8-be9e-4a7872c6ff28)


iii) # To find the maximum marks without using builtin functions.
![Screenshot 2024-04-02 080217](https://github.com/lalitchandran/FindMaximum/assets/137707725/06a9e02d-6dbf-4e7c-8433-f42df51a6580)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
