# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:

import panda as pd

### Step 2:

For reading data swe put code.

### Step 3

we give print(head(10)) to get a output of first 10 lines.

### Step 4:
we give print(tail()) to get a output of last 5 lines.

### Step 5:

next we have to put code for gret length of row and column.

## PROGRAM:
##Name : P Shobika
##Reg No: 212221230096
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head())
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))

## OUTPUT:
![GitHub Logo](.//img2.png)
## RESULT:
