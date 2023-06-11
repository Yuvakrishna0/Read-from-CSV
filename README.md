# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1:
import panda module as pd
### Step 2:
Read the csv file
### Step 3:
print the first 10rows 
### Step 4:
print the next 5rows
### Step 5:
print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
Program to read contents from a CSV file.
Developed by: Yuva krishna k
Reg No: 212222110056

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```

## OUTPUT:

![244879918-cac77127-f9c5-4e11-84d5-abac42e1067a](https://github.com/Yuvakrishna0/Read-from-CSV/assets/117915037/1cdf3bd5-1cd4-420d-a8b2-e668767cc54e)

## RESULT:
The program is executed successfully
