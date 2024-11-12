# DATE:
# EXP-12: Read-from-CSV

## AIM:
To read the contents from a csv file.

## ALGORITHM:
### Step 1:Start the program.
### Step 2:Create a file nba.csv in anaconda navigator.
### Step 3:Write a program to read the contents in the csv file.
### Step 4:Run the program
### Step 5:Print the output

## PROGRAM:
```
DEVLOPED BY:A K PREETHI
REGISTER NUMBER:212223230156

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/dd2e9e09-9911-47a5-a1f2-0e324954d8bc)


## RESULT:
Contennts are read succesfully.
