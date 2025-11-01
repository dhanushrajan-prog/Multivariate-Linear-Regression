# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
import pandas as pd

from sklearn import linear_model

df = pd.read csv("car.csv"

= df[['Weight', 'Volume']]

y = df['c02']

regr = linear_model.LinearRegression()

regr.fit(X, y)

print('Coefficients:', regr.coef)

print('Intercept:', regr.intercept_)

predictedc02 = regr.predict(pd.DataFrame([[3300, 1300]], columns=['Weight', 'Volume']))

print('Predicted C02 for the corresponding weight and volume:', predictedc02)





```
## Output:
<br>
<img width="1712" height="170" alt="image" src="https://github.com/user-attachments/assets/afdd9b9b-afe4-4d09-a354-581a35e55764" />


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
