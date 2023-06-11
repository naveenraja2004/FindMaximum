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
Developed by: N.R Naveen Raja
RegisterNumber: 212222230093
'''
def max_marks(marks):
    #write your code here
    marks.sort()
    large = max(marks)
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: N.R Naveen Raja
RegisterNumber: 212222230093
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: N.R Naveen Raja
RegisterNumber: 212222230093
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![python exp 3a 1](https://github.com/naveenraja2004/FindMaximum/assets/118707204/178a4a1a-dd5e-47be-9c1c-d1261aa5da96)







![python exp 3a 2](https://github.com/naveenraja2004/FindMaximum/assets/118707204/fa27f4c3-701b-4c2e-a671-37910927d6c0)






![python exp no 3 c](https://github.com/naveenraja2004/FindMaximum/assets/118707204/ad6c3020-37fb-4b23-9e22-0deaa9c13e6d)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
