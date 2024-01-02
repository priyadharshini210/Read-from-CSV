# Read-from-CSV

## AIM:
To Write a python program for reading content from a CSV file

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv
### Step 3:
use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
print the output
## PROGRAM:
```
#Program to read contents from a csv file
#Developed by: Priyadharshini.P
#RegisterNumber: 23013604
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/priyadharshini210/Read-from-CSV/assets/148514638/f6a21015-20ba-40f1-90a3-c513125c3c0e)
![image](https://github.com/priyadharshini210/Read-from-CSV/assets/148514638/4bc04c51-5a5d-4b9f-bae5-9f69542763be)

## RESULT:
Thus a python program is written to read the contents of a CSV file
