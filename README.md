# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file

## ALGORITHM:
### Step 1:
Start the program.

### Step 2:
Create a file nba.csv in anaconda navigator

### Step 3
Write a program to read the contents in the csv file

### Step 4:
Run the program

### Step 5:
Print the output

## PROGRAM:
# To write a python program for reading content from a csv file
# Developed by: VD Natchathira
# Register number: 212224230178
```
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
<img width="724" height="729" alt="image" src="https://github.com/user-attachments/assets/875d7f43-b33e-4407-8fe0-4ae426cf627a" />

## RESULT:
Hence, the contents are ready successfully.
