# mle-training
Assignment 3.1

# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data.

The following techniques have been used:

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## Steps to install packages and execute the script
- We prepare and clean the data. We check and impute for missing values.
- Different encoding techniques are used and to convert categorical columns into numerical
- EDA is performed on housing data & The data set is split into train and test.
- Different regression models(Linear Regression, Random Forest Regressor, Support Vector Regressor) are used and evaluated performance metrics.
- Random Search CV and grid search CV techniques are used for hyperparameter tuning
- Column transformers are used to create new features and robustify code.


run below commands in terminal but make sure conda is installed or use anaconda prompt which you will get as part of anaconda installation

```
conda create -n ml_flow python=3.9 ipykernel
```
Activate the environment
```
conda activate envname
```
Install all required dependencies to run this notebook
```
pip install pandas
pip install numpy
pip install scikit-learn
pip install imblearn
pip install matplotlib
pip install mlflow
```
Now open the notebook using below command: (from the anaconda prom
pt inside conda environment)
```
jupyter notebook
```

for launching ML Flow Ui:
```
mlflow ui
```

- It will take to ml flow server and we can log the metrics
