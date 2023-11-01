# Ex-07-Feature-Selection
### Aim:
To Perform the various feature selection techniques on a dataset and save the data to a file. 
### Explanation:
Feature selection is to find the best set of features that allows one to build useful models.
Selecting the best features helps the model to perform well. 

### Algorithm:
- Step1: Read the given Data
- Step2: Clean the Data Set using Data Cleaning Process.
- Step3: Apply Feature selection techniques to all the features of the data set.
- Step4: Save the data to the file. 
### Code:
```Python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
data=pd.read_csv("titanic_dataset.csv")
data.head()
```
![image](https://github.com/ROHITJAIND/EX-07-FEATURE-SELECTION/assets/118707073/ae7546f8-d2cf-467e-b91e-d21e7e0976e7)
<table>
<tr>
<td>

```Python
data.isnull().sum()                    
```
</td>
<td>

![image](https://github.com/ROHITJAIND/EX-07-FEATURE-SELECTION/assets/118707073/4ae50abe-c864-4249-a961-c729ec28673d) 
</td>
</tr>
</table>

### Output:

### Result:
