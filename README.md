# Ex-08-Data-Visualization-

## AIM
To Perform Data Visualization on a complex dataset and save the data to a file. 

# Explanation
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# ALGORITHM
### STEP 1
Read the given Data
### STEP 2
Clean the Data Set using Data Cleaning Process
### STEP 3
Apply Feature generation and selection techniques to all the features of the data set
### STEP 4
Apply data visualization techniques to identify the patterns of the data.

# CODE
```
/* 
Name : Ranjith G.
Register Number : 212220220034
**Data Visualization - Superstore.csv**
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sbn
df=pd.read_csv("/content/Superstore.csv", encoding = 'windows-1252')
df.head()
df.info()
df.isnull().sum()
sbn.countplot(x=df['Segment'],data=df)
plt.title("Number of Sales in Segment")
sbn.barplot(df['City'],df['Profit'])
plt.title("Number of Profit in Cities")
sbn.countplot(x=df['Ship Mode'],data=df)
plt.title("Number of profits in Ship Mode")
sbn.boxplot(df['Region'], df['Sales'])
plt.title("Sales of Product based on Region")
sbn.scatterplot(x=df['Sales'], y=df['Profit'])
sbn.scatterplot(df['Sales'],df['Profit'],hue=df['Segment'])
sbn.scatterplot(df['Sales'],df['City'],hue=df['Profit'])
sbn.scatterplot(df['Sales'],df['Profit'],hue=df['Ship Mode'])
sbn.scatterplot(df['Sales'],df['Profit'],hue=df['Region'])
*/
```
# OUPUT
## Data Visualization - Superstore.csv
![img](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/894236da-f9c8-4402-a8aa-96be5267afa0)

![img2](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/3061767f-b8a9-4d49-9dfb-a45ad2a996e7)

![img3](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/73d888ae-f245-4e01-b37e-16f6b7fa892e)

![img4](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/513e8516-924d-403a-a718-9fd4268a87ef)

![img5](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/1d997677-6574-4fea-a8f5-fc6d08d3d270)

![img6](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/3e9e6f06-e82e-4b13-a5a3-2f94a33b4b4c)

![img7](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/c476fd65-24a3-4f34-9ea6-7730a150d58a)

![img8](https://github.com/ranjithhacker/Data-visualization-I/assets/129825315/4280ab1f-c43b-42f0-b9b5-e7292e37a569)


# RESULT
Thus the Data Visualization for the given dataset had been executed successfully.
