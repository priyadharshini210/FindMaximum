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
Developed by: 
RegisterNumber: 

def max_marks(list1):
    max=0
    for i in list1:
        if i>max:
            max=i
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![OUTPUT](image.png)
![OUTPUT](image-1.png)
![OUTPUT](image-2.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.