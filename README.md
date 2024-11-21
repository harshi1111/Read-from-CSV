# Date:
# Ex.No: 12 Read-from-CSV

## AIM: To write a python program for reading the csv file content

## ALGORITHM:
### Step 1: Load the CSV into a DataFrame.
### Step 2: Print the number of contents to be displayed using df.head().
### Step 3: The number of rows returned is defined in Pandas option settings.
### Step 4: Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
Developed By: HARSHITHA V
Register No: 212223230074
```
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/44484749-8c7f-4f6f-8e5d-aaf1623dab04)


## RESULT: 
Thus the program is written to read the csv file.
