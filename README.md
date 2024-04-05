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

i)	 To find the maximum of marks using the list method sort.
     ```
     Developed by : Prashanth.K
     Register number: 212223230152
     ```
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num


```



## Output:
(i) To find the maximum of marks using the list method sort.
![Screenshot 2024-04-05 201847](https://github.com/PRASHANTHRATHI/FindMaximum/assets/145743120/bb251470-291c-4ebf-be43-143ff848cfd3)
![Screenshot 2024-04-05 201900](https://github.com/PRASHANTHRATHI/FindMaximum/assets/145743120/818a95fa-98b7-4038-8d66-d079b9f1cf2f)


(ii) To find the maximum marks using the list method max().
![Screenshot 2024-04-05 201912](https://github.com/PRASHANTHRATHI/FindMaximum/assets/145743120/2ebd550e-a478-4214-be47-59ac87589742)
![Screenshot 2024-04-05 201923](https://github.com/PRASHANTHRATHI/FindMaximum/assets/145743120/26c2b373-b585-40da-b591-b15931c3c904)

(iii) To find the maximum marks without using builtin functions.
![Screenshot 2024-04-05 201932](https://github.com/PRASHANTHRATHI/FindMaximum/assets/145743120/74a2d412-5211-4337-9202-6637055e4357)
![Screenshot 2024-04-05 201938](https://github.com/PRASHANTHRATHI/FindMaximum/assets/145743120/bbf51443-ca0f-4bcb-8f0b-fd7aa481b01b)







## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
