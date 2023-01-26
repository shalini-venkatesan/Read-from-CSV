# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```py
##Program to read from csv file
##developed by: Shalini V
##Register no: 22009257
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[0]))
```

## OUTPUT:
![output](/13.png)

## RESULT:
Thus the program is written to read the csv file.
