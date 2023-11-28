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
Developed by:A.Hari Veera Prasad
RegisterNumber:23009466 
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    b=marks[-1]
    return b



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:A.Hari Veera Prasad
RegisterNumber:23009466
'''
def max_marks(marks):
    # write your code here
    b=max(marks)
    return b


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:A.Hari Veera Prasad 
RegisterNumber:23009466
'''
def max_marks(list1):
    # write your code here
    for i in list1:
        if i>list1[3]:
            return i


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
# Program to mark the maximum of marks using the list method sort:
![image](https://github.com/Hariveeraprasad-2006/FindMaximum/assets/145049988/f040e5e9-2eea-447d-88b8-8f13a3915133)
# To find the maximum marks using the list method max().
![image](https://github.com/Hariveeraprasad-2006/FindMaximum/assets/145049988/791b40a8-c02e-4dcd-a620-a9de3584b697)
# To find the maximum marks without using builtin functions.
![image](https://github.com/Hariveeraprasad-2006/FindMaximum/assets/145049988/10f64664-414f-42f8-a1ee-5ceb7c2e1c48)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
