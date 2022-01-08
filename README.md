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
~~~
Program to mark the maximum of marks using the list method sort
Developed by: your name: Shrruthilaya G
RegisterNumber: 21002893
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
~~~

ii)	# To find the maximum marks using the list method max().
~~~
Program to find the maximum marks using the list method max().
Developed by: your name: Shrruthilaya G
RegisterNumber: 21002893
def max_marks(marks):
    a=max(marks)
    return a
~~~

iii) # To find the maximum marks without using builtin functions.
~~~
Program to the maximum marks without using builtin functions.
Developed by: your name: Shrruthilaya G
RegisterNumber: 21002893
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark
~~~

## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![GitHub _Logo](sort.png)



![GitHub_Logo](max().png)


![GitHub_Logo](builtin.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.