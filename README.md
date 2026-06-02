# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:

Import the required libraries such as Pandas and Linear Regression from Scikit-Learn.

Step 2:

Load the dataset from the CSV file and select the independent variables (Weight and Volume) and the dependent variable (CO2).

Step 3:

Create a Linear Regression model and train it using the dataset with the fit() method.

Step 4:

Display the regression coefficients and intercept of the trained model.

Step 5:

Predict the CO2 emission for the given values of weight and volume using the predict() method and display the result.
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
