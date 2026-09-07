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
```
import matplotlib.pyplot as plt
marks=[13,45,63,78] 
student=['ABC','QOR','EFB','TOB'] 
plt.plot(marks,student) 
plt.xlabel('Marks') 
plt.ylabel('Student name') 
plt.show()
```
<img width="718" height="530" alt="640746016-8a91ce8c-ef94-4a52-bb24-5a6b3acab220" src="https://github.com/user-attachments/assets/a33a7d78-c2cd-46fb-a708-83e57dd82327" />

```
import numpy as np
x=np.arange(0,15) 
y=np.arange(0,15) 
x 
y 
plt.scatter(x,y,c='r') 
plt.xlabel('X axis') 
plt.ylabel('y axis') 
plt.title('Scatter plot') 
plt.show()
```
<img width="717" height="562" alt="640746249-c6f113ef-6c68-4f8b-9be9-998cdf9e723e" src="https://github.com/user-attachments/assets/f09aff0c-9936-4dca-91c4-86b0d5fc53a7" />

```
act=['eat','sleep','work','play'] 
slices=[3,7,8,6] 
color=['r','y','g','b'] 
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%') 
plt.legend() 
plt.show()
```
<img width="621" height="527" alt="640746485-4ef5a71b-7b4e-4ab9-bb78-6f859ab457be" src="https://github.com/user-attachments/assets/4e36b644-b1cf-4924-9c03-c1385080783a" />

```
x = [1, 2, 3, 4, 5] 
y1 = [10, 12, 14, 16, 18] 
y2 = [5, 7, 9, 11, 13]
plt.fill_between(x, y1, color='blue') 
plt.fill_between(x, y2, color='green') 
plt.plot(x, y1, color='red') 
plt.plot(x, y2, color='black') 
plt.legend(['y1','y2']) 
plt.show()
```
<img width="703" height="517" alt="640746678-f24c478d-f045-44ec-990c-6798955a6396" src="https://github.com/user-attachments/assets/e4135036-64a0-4438-b52e-727a814f144b" />

```
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
<img width="707" height="555" alt="640746915-a9686f9d-b622-4418-b895-22fd8b9d7e90" src="https://github.com/user-attachments/assets/345ab943-43a2-40ce-8105-4071c5c71a76" />

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1] 
plt.hist(x, bins = 10, color='blue', alpha=0.5) 
plt.show()
```
<img width="672" height="515" alt="640747147-c2118ce7-2ccb-48a4-aad1-7a54b3d85b51" src="https://github.com/user-attachments/assets/6a84686b-e727-41fa-918b-e416251446b9" />

```
import numpy as np
import matplotlib.pyplot as plt

np.random.seed(0)
data = np.random.normal(loc=0, scale=1, size=100)
data

plt.subplots()
plt.boxplot(data)
plt.xlabel('Data')
plt.ylabel('Values')
plt.title('Box Plot')
plt.show()
```
<img width="725" height="560" alt="640747405-f100f08d-9e69-427d-a981-f2574ab6bca5" src="https://github.com/user-attachments/assets/87bd0772-5f0e-41ca-ab69-bfbdca6b44e9" />

# Result:
 Thus Data Visualization is completed successfully using Matplotlib.
