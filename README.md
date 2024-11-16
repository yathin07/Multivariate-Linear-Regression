# DATE:
## EXP-10: Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Start the program

### Step2
<br>Write a program to perform multivariate regression in anaconda navigator.

### Step3
<br>Run the program

### Step4
<br>Print the output.

### Step5
<br>End the program.

## Program:
```

DEVELOPED BY:Yathin Reddy T
REGISTER NUMBER:212223100062


import pandas as pd
from sklearn import linear_model
data=pd.read_csv("car.csv")
x=data[['Weight','Volume']]
y=data[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print('predicted CO2 for the corresponding weight and volume',predictCO2)






```
## Output:



<br>![image](https://github.com/user-attachments/assets/9869a7a2-0fdc-45f3-9f40-c62875ef7f8c)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
