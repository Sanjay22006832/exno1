# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

```py
# Developed By: Sanjay M
# Register Number: 212222240090
```
<table>
  <tr>
    <td width=50%>


### 1) Read and display DataFrame
```Python
import pandas as pd
df=pd.read_csv('/content/SAMPLEIDS.csv')
df
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/12f89e79-8528-4396-a300-dac097c88c6b)

)
</td>
</tr>
<tr>
  <td width=50%>
              
### 2) Display head
```Python
df.head()
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/98f7f841-be11-464d-b625-1fcf1618ecfd)


</td>
</tr>
<tr>
  <td width=50%>

### 3) Display tail
```Python
df.tail()
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/422bc98a-a6e5-46d8-9e19-80dbeabfc55a)


</td>
</tr>
<tr>
  <td width=50%>

### 4) Info of datafram
```Python
df.info()
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/a381ed1c-39c1-4f0a-a9fe-3069e254b58a)


</td>
</tr>
<tr>
  <td width=50%>

### 5) Describe about the dataframe
```Python
df.describe()
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/455eae02-5360-4484-9b83-8253f47b6a85)


</td>
</tr>
<tr>
  <td width=50%>

### 6) Shape of the datafram
```Python
df.shape
```
  </td>
  <td>
              
#### OUTPUT:
![image](https://github.com/Sanjay22006832/exno1/assets/119830477/2ac271fa-6b88-4a3d-922d-225c8c35529d)


</td>
</tr>
<tr>
  <td width=50%>

### 7) Checking tha NUll values
```Python
df.isnull()
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/7784a32c-3f69-4ac6-bb63-569e96cf42ba)


</td>
</tr>
<tr>
  <td width=50%>

### 8) Drop the Null values
```Python
df.dropna(axis=0)
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/12873915-7b04-4f86-a0e6-7e4468ea47a6)


</td>
</tr>
<tr>
  <td width=50%>



### 9) Fill the Null values
```Python
df.fillna(0)
```
  </td>
  <td>
              
#### OUTPUT:

![image](https://github.com/Sanjay22006832/exno1/assets/119830477/5b6b2f3a-76db-4ec7-8896-f0976dab82f0)


</td>
</tr>
<tr>
  <td width=50%>



# Result
The data cleaning has beeen done successfully.
