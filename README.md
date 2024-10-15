# DATE:
# EX.NO.08 Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```python
#Write a program to sort the elements in the list using the Selection Sort algorithm.
#Deveolped by: MOHAN S
#Register no:212223240094

num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)

```
ii)	#Insertion Sort
```python
#Write a program to sort the elements in the list using the Insertion Sort algorithm.
#Deveolped by: MOHAN S
#Register no:212223240094
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)


```

## Output:
```
(i)Write a program to sort the elements in the list using the Selection Sort algorithm.
![Screenshot 2024-10-15 182653](https://github.com/user-attachments/assets/ba603a93-5fe4-4e90-a703-32731e448548)

```
```
(ii)Write a program to sort the elements in the list using the Insertion Sort algorithm.
![Screenshot 2024-10-15 182709](https://github.com/user-attachments/assets/1d16acb5-88eb-4017-b4a6-54746a8ea73d)
```

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
