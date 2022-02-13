# Read-from-CSV

## AIM:
To write a program to read from csv

## ALGORITHM:
### Step 1:
load the csv into a data frame

### Step 2:
print the number of contents to be displayed using df.head()

### Step 3:
the number of rows returened is defined in pandas option settings

### Step 4:
check your systems maximum colum with the pd.options.display.max_colums statement

### Step 5:
increase the maximum number of rows to display the entire data frame

## PROGRAM:
##Developed by : R.Hema Priya
##Reg>no : 21004884
```python
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("no. of column",len(df.axes[0]))
print("no. of rows",len(df.axes[1])
```
## OUTPUT:
![output](https://github.com/Hemapriya-2004/Read-from-CSV/blob/main/h3.PNG/raw=true)

## RESULT:
Thus the program runs successfully
