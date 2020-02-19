# Project 1 : Learning under Covariate Shift in the Data (Supervised Learning)
<br>
This project focuses on identifying the effect of covariate shift on the performance of machine learning models.


The datasets used for the evaluation were taken from Kaggle
1. [Santander Customer Transaction Prediction](https://www.kaggle.com/c/santander-customer-transaction-prediction/data)
2. [Google Analytics Customer Revenue Prediction](https://www.kaggle.com/c/ga-customer-revenue-prediction/overview/evaluation)


The script to upload the Kaggle API token, automatically download and unzip the datasets has been included in the `Assignment.ipynb` notebook.

##### NOTE: PLEASE RUN THE NOTEBOOK ON GOOGLE COLAB. THE PATHS MENTIONED IN THE SCRIPT ARE SPECIFIC TO A GOOGLE COLAB VM.

If running the notebook for the first time in a new VM, please set the following Variables to `True`, otherwise `False`:
1. `UPLOAD_TOKEN` - to upload kaggle.json to enable kaggle api for your account. (Follow "Authentication" section in [this](https://www.kaggle.com/docs/api) to get kaggle.json for your account)
2. `DOWNLOAD_DATA` - Download and Unzip the data.

This is a rough initial exploratory data analysis. Methods to detect and adapt the covariate shift, designing and training on models, and performance evaluation of the classifiers will be carried in the next phase of the project.
