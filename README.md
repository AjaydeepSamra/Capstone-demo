## Ajay's Capstone
=========================

### Project Overview  
Crypto Day trading Signals
My Goal here is to create a model that predicts the price of btc in short term, if successful this model can be used to day trade BTC 

Description of dataset being used:

Date is being used as the index,
While other columns are [open, high, low, close, Volume BTC,Volume USD]

Feature that can be added to this are predicting columns [open, high, low, close] each column can be a sepeate feature as day trading requires selling instead of holding for long term

Some feature that i added were moving averages( Simple and Exponential)

Baseline models used were SARIMAX, Linear Regression and Decision Tree Classifier. Out of these three models Linear regression was the best one. 

After that grid search with 5 fold verification was used to find the best possible model. The best model is DecisionTreeRegressor with the following parmeters:
max_depth: 20
min_samples_leaf: 4
min_samples_split: 2



### Project Flowchart
Project is done step by step and is easy to follow along/ ( Notebooks folder- notebooks are numbered)

### Project Organization


* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible Google Drive folder)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - joblib dump of final model / model object

* `notebooks`
    - contains all final notebooks involved in the project


* `capstine_env.yml`
    - Conda environment specification


* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

### Dataset
https://www.cryptodatadownload.com/data/gemini/
