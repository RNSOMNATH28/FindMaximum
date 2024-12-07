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
#developed by:  R N Somnath
#register number:24000580

def max_marks(array):
    array.sort()
    return array[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python

#developed by:R N Somnath
#register number:24000580

def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by:R N Somnath
#register number:24000580

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1



```



## Output:
![Screenshot 2024-12-07 193041](https://github.com/user-attachments/assets/d52d0a8a-5e05-4adc-883c-1ecbaf529d8f)
![Screenshot 2024-12-07 193029](https://github.com/user-attachments/assets/e1b27b06-6057-4697-88af-16fe8e161bf2)
![Screenshot 2024-12-07 193018](https://github.com/user-attachments/assets/3d563d4e-1f32-4635-a75a-a2f9e78b3629)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
