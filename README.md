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
Program to mark the maximum of marks using the list method sort
Developed by: Priyadharshini.P
RegisterNumber: 23013604

def max_marks(marks):
    marks.sort()
    max_mark=marks[-1]
    return max_mark


```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Priyadharshini.P
RegisterNumber: 23013604

def max_marks(marks):
    max_marks=max(marks)
    return max_marks

```

iii) # to find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Priyadharshini.P
RegisterNumber: 23013604

def max_marks(list1):
    max=0
    for i in list1:
        if i>max:
            max=i
    return max

```

## Output:
i)	# To find the maximum of marks using the list method sort
![Screenshot 2023-12-17 083429](https://github.com/priyadharshini210/FindMaximum/assets/148514638/0102c778-643d-4edd-a4ae-35009ce69a7e)
ii)	# To find the maximum marks using the list method max().
![Screenshot 2023-12-17 083518](https://github.com/priyadharshini210/FindMaximum/assets/148514638/ae7b8ad5-81a5-4722-8923-913d6fec88fb)
iii) # to find the maximum marks without using builtin functions.
![Screenshot 2023-12-17 083600](https://github.com/priyadharshini210/FindMaximum/assets/148514638/1f382aa9-53c9-44d3-a8f8-4d8916a51661)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
