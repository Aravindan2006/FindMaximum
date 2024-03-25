# Find the maximum of a list of numbers
## 212223240012
## ARAVINDAN D
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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```



## Output:
![Screenshot 2024-03-25 213946](https://github.com/Aravindan2006/FindMaximum/assets/151760062/ac603c3b-c7c4-4269-b521-4a4bc4b38d90)

![Screenshot 2024-03-25 213959](https://github.com/Aravindan2006/FindMaximum/assets/151760062/f352ade7-a33f-41b9-8f1f-98dbd642eb03)

![Screenshot 2024-03-25 214010](https://github.com/Aravindan2006/FindMaximum/assets/151760062/69821be5-1476-4833-8e36-e766d07e1744)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
