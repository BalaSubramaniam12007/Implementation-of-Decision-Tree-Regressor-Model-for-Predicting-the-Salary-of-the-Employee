# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: BALASUBRAMANIAM L
RegisterNumber:  24901213

import pandas as pd
data=pd.read_csv("/content/Salary.csv")
data.head()
data.info()
data.isnull().sum()
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data["Position"]=le.fit_transform(data["Position"])
data.head()
x=data[["Position","Level"]]
x.head()
y=data["Salary"]
y.head()
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=2)
from sklearn.tree import DecisionTreeRegressor
dt=DecisionTreeRegressor()
dt.fit(x_train,y_train)
y_pred=dt.predict(x_test)
y_pred
r2=metrics.r2_score(y_test,y_pred)
r2
dt.predict([[5,6]])

*/
```

## Output:

![Screenshot 2024-11-28 220529](https://github.com/user-attachments/assets/4b7632a0-0623-4ddf-bd42-3a1510ca16bf)
![Screenshot 2024-11-28 220513](https://github.com/user-attachments/assets/ad97fce3-47a3-4e85-8fb2-9bef456efe49)
![Screenshot 2024-11-28 220529](https://github.com/user-attachments/assets/1921087c-f4f8-49ce-8ed5-f75bd9bdb33d)


![image](https://github.com/user-attachments/assets/a9251b78-4cbe-44cc-8710-8c0b596f3e4c)



## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
