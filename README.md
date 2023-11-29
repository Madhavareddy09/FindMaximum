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
Developed by: K.Madhava reddy
RegisterNumber: 23009929
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: K.Madhava reddy
RegisterNumber: 23009929
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: K.Madhava reddy
RegisterNumber: 23009929
def max_marks(list1):
    max1=0
    for i in list1:
        if i>max1:
            max1=i
    return max1

```
## Sample Input and Output

![image](https://github.com/Madhavareddy09/FindMaximum/assets/145742470/f75dbb0b-036c-4d11-a597-6c5294e73bd4)
![image](https://github.com/Madhavareddy09/FindMaximum/assets/145742470/a5b02334-4e84-4647-b238-01f6a9fceb8e)

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Madhavareddy09/FindMaximum/assets/145742470/68ea6108-730f-46d7-a678-c22cd48e8d61)
ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Madhavareddy09/FindMaximum/assets/145742470/70eeb94e-fc91-44bd-ace2-4377fdbc0301)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Madhavareddy09/FindMaximum/assets/145742470/491b1aea-fac7-4de3-9415-279326bf7ef9)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
