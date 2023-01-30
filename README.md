# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
load the csv into dataframe
### Step 2:
print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in pandas option settings.
### Step 4:
Check your system's maximum coloumn with the pd.options.max_coloumn statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```python
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```

OUTPUT:

![csv](https://user-images.githubusercontent.com/121029258/215381853-4783ca1a-441a-43a7-b603-c73912a3ea72.jpg)

## RESULT:
Thus the program is written to read the csv file
