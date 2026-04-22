# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
Dataset Name = Customer_Transactions

To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.



# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:

```
Name: PRADEEP V
Reg No. 212223240119

```

```
from matplotlib import pyplot as pyplot
import pandas as pd

df = pd.read_csv("/content/customer")

df.head()

print(df.dtypes)

pyplot.xlabel('customer_id')
pyplot.ylabel('annual_income')

pyplot.plot(df.index, df['annual_income'], label='Annual Income')
pyplot.legend()
pyplot.grid(True)

```











# OUTPUT:
<img width="842" height="552" alt="image" src="https://github.com/user-attachments/assets/082cb9ec-c84b-498f-9346-8eae9b8d464f" />







# RESULT:
Thus we have created the python code for plotting the time series of given data.
