# **SE_25**

This repository contains all jupyter notebooks relevant for the assessment in SE_25 'data science'.

# 1. Content
This repository contains the three guided exercises from DataCamp in the 'DataCamp' project directory. The project directory ‘Kaggle_OwnProject' contains my unguided research project.

In the ‘Kaggle_OwnProject' you can find six jupyter notebooks, a folder ‘datasets’, and two images. The six jupyter notebooks are:
- ### **DATA_CLEANING:** 
  this notebook should be opened first to ensure that the code cleans and pre-processes the data so that other notebooks can use it
- ### **MAIN_DOCUMENT:** 
  this notebook summarises all the results of my analysis and contains the report
- ### **PLOT_FUNCTIONS:**
  this notebook has the code for all data visualization functions.
- ### **XGBOOST_MODELLING:**
  this notebook shows the code from the machine learning process performed in the analysis process
- ### **SHAP_VALUES:** 
  this notebook shows the code used for analyzing the ML model.
- ### **CHI2_TEST:**
  this notebook contains the code used to evaluate the results from the SHAP analysis. 

The 'datasets' folder contains the file 'aug_train.csv'. It contains the dataset used in this project. The folder is supplemented during data pre-processing and cleansing with files resulting from the steps in the 'DATA-CLEANING' notebook.

The repository also includes the self-assessment and my portfolio for the assessment in SE25.

# 2. Required libraries/modules:
### general modules / libraries
- sys
- warnings  
- nbimporter
- from copy: deepcopy
### data analysis and visualization modules/libraries
- numpy
- from numpy: loadtxt
- pandas
- matplotlib
- matplotlib.pyplot
- matplotlib.ticker
- from matplotlib.ticker: PercentFormatter
- seaborn
- scipy.stats
- from scipy: stats
### machine learning modules / libraries
- xgboost
- from xgboost: plot_importance
- from xgboost: XGBClassifier
- from xgboost: XGBRegressor
- from imblearn.over_sampling: RandomOverSampler
- sklearn
- from sklearn.dummy: DummyClassifier
- from sklearn.metrics: mean_squared_error
- from sklearn.metrics: accuracy_score
- from sklearn.model_selection: cross_validate
- from sklearn.model_selection: GridSearchCV
- from sklearn.model_selection: train_test_split

# 3. Steps to reproduce:
Please follow these steps:
1. install the required libraries 
2. select the repository 'SE_25'
3. download the repository with the 'Code' button: 'download zip'
4. save the unzipped folder in a directory
5. select the directory in your terminal
6. use the command jupyter notebook
7. a browser window opens automatically: Select the notebook you want to explore

**Please remember:** for the ‘Kaggle_Own_Project’ to start with the notebook ‘DATA_CLEANING’ first. 
