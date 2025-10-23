# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np

marks = [13, 45, 63, 78]
student = ['A', 'B', 'C', 'D']
plt.plot(marks, student)
plt.xlabel('Marks')
plt.ylabel('Student')
plt.title('Student Marks')
plt.show()
```
### Output:
<img width="695" height="566" alt="image" src="https://github.com/user-attachments/assets/07fb4560-a2ee-409b-959e-40971e1dd031" />

```python
student = ['A', 'B', 'C', 'D']
attendance = [78, 65, 89, 90]
plt.plot(attendance, student)
plt.xlabel('Attendance')
plt.ylabel('Student')
plt.title('Student Attendance')
plt.show()
```
### Output:
<img width="695" height="570" alt="image" src="https://github.com/user-attachments/assets/109abcca-df4f-48c5-afb8-93ea4d836700" />

```python
x = [10, 20, 30, 40, 50]
y = [100, 200, 300, 400, 500]
plt.scatter(x, y, label='stars', color='green', marker='*', s=30)
plt.show()
```
### Output:
<img width="686" height="513" alt="image" src="https://github.com/user-attachments/assets/f8d70b3d-44e3-496d-9f87-0c1ca188acdd" />

```python
x = np.arange(0, 15)
y = np.arange(0, 15)
plt.scatter(x, y, color='red')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Simple Scatter Plot')
plt.show()
```
### Output:
<img width="696" height="572" alt="image" src="https://github.com/user-attachments/assets/c1ecd517-f7f4-4d4f-8185-322e0230ae5a" />

```python
act = ['eat', 'sleep', 'work', 'play']
slices = [3, 7, 8, 6]
color = ['r', 'y', 'g', 'b']
plt.pie(slices, labels=act, colors=color, startangle=90, shadow=True, explode=(0.1, 0.1, 0.1, 0.1), radius=1.2, autopct='%1.1f%%')
plt.legend()
plt.show()
```
### Output:
<img width="567" height="517" alt="image" src="https://github.com/user-attachments/assets/1af55973-1046-4e04-bff4-e8e7959d562e" />


```python
feedback=['Good', 'excellent', 'Perfect', 'Ok']
slices=[4, 10, 3, 8]
color=['y', 'r', 'b', 'g']
plt.pie(slices, labels=feedback, colors=color, startangle=90, shadow=True, explode=(0.1,0.1,0.1,0.1), radius=1.2, autopct='%1.1f%%')
plt.legend()
plt.show()
```
### Output:
<img width="548" height="496" alt="image" src="https://github.com/user-attachments/assets/08316420-0350-4651-b2cf-d95caf64b8d2" />

```python
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
### Output:
<img width="694" height="517" alt="image" src="https://github.com/user-attachments/assets/c5c49a28-0caa-4080-ab28-ab0056751a9a" />

```python
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
### Output:
<img width="703" height="564" alt="image" src="https://github.com/user-attachments/assets/91ef661f-ae2d-405e-8489-c006da817dcd" />

```python
x = [2, 1, 6, 4, 2, 4, 8, 9, 4, 2, 4, 10, 6, 4, 5, 7, 7, 3, 2, 7, 5, 3, 5, 9, 2, 1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
### Output:
<img width="669" height="516" alt="image" src="https://github.com/user-attachments/assets/63810886-ed17-488e-a6c3-41464e769840" />

```python
np.random.seed(0)
data = np.random.normal(loc=0, scale=1, size=100)

plt.boxplot(data)
plt.xlabel('Data')
plt.ylabel('Values')
plt.title('Box plot')
plt.plot()
plt.show()

```
### Output:
<img width="707" height="563" alt="image" src="https://github.com/user-attachments/assets/c67a62f9-d40d-4bad-8f9e-00d86b5622ff" />


# Result:
Thus all the data visualization techniques of matplotlib has been implemented.
