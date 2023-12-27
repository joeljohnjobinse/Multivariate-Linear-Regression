# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
Import pandas

### Step2
<br>
Import linear model from sklearn

### Step3
<br>
Read the file cars.csv

### Step4
<br>
Assign the values x and y as required

### Step5
<br>
Create the linear regression model and predict the output

## Program:
```
#Program for implementation of Multivariate linear regression
#Developed by: Joel John Jobinse
#Register Number: 212223240062
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))

```
## Output:
### Insert your output
![maths-exp10](https://github.com/joeljohnjobinse/Multivariate-Linear-Regression/assets/138955488/c9816330-40a5-4938-a2d3-f7dd3f32469c)
<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
