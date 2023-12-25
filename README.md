# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pands module to solve for multivariate linear egression

### Step2
import pandas module to solve for multivariate linear egression

### Step3
open the file cars saved in the drive and get input for weight and volume to find density of co2

### Step4
print coefficient ,intercept and amount

### Step5
end of the program

## Program:
```
import pandas as pd
from sklearn import linear model
df=pd.read_csv('/content/drive/My Drive/car (1).csv')
x-df[['weight','Volume']]
y=df[['coz']]
regr=linear_model.linearRegression()
regr.fit(x,y)
print('coefficient:',regr.coef_)
print('Intercept:',regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:
![IMG_20231225_145935](https://github.com/23007232/Multivariate-Linear-Regression/assets/139115574/dffcdcae-c293-4cc5-9ee0-1bc217b5e7f1)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
