# BigMart Sales Prediction

### Data set link

```bash
https://www.kaggle.com/code/hiralmshah/bigmart-sales-prediction/data
```

### Problem Statement :

Nowadays, shopping malls and Big Marts keep track of individual item sales data in order to forecast future client demand and adjust inventory management. In a data warehouse, these data stores hold a significant amount of consumer information and particular item details. By mining the data store from the data warehouse, more anomalies and common patterns can be discovered.

### Creating an environment 
```bash
conda create --prefix ./env python=3.7 -y
activate ./env
pip install -r requirements.txt
```

### Approach :

The main goal is to build a model to predict the BigMart outlet sales based on different factors available in the dataset.

1. Data Collection : The dataset was downloaded from the Kaggle.
2. Exploratory Data Analysis : Plotted different graphs to get more insights about dependent and independen variables/features(Univariate Analysis, Bi-variate Analysis and Multi-variate Analysis). 
3. Feature Engineering : Handled missing values, created new variables/features as per insights. Also numerical features scaled down and Categorical features encoded.
4. Model Building : In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:

```bash
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Adaboost Regressor
XGBoost Regressor
```

Support Vector Machine Evaluation is done on basis of RMSE score and R-squared.
Model Selection : After performing some tunning the best model is selected.

Pickle File : The best accuaracy model was then saved using Pickle.

Webpage : Using Frontend tools created a webform that takes all the necessary inputs from the uset to predict the output.


### Accuracy obtained for all the models are:
Linear Regression = 50%
Random Forest = 55%