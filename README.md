# walmart_sales_forecasting
### Contents
This repository contains a Jupyter notebook and Tableau packaged workbook, which outline my approach for the   
"Walmart Recruiting II: Sales in Stormy Weather" contest hosted on Kaggle. The Tableau workbook contains visualizations that guide feature generation and predictive modeling in the Juptyer notebook.

### Description of CSV Files
1. Download competition data from the following link and place csv files into datasets repository: https://www.kaggle.com/c/walmart-recruiting-sales-in-stormy-weather/data
2. Run the walmart_sales_forecasting.ipynb notebook to clean the "train.csv" file and generate the meaningful set of training features "train_cleaned.csv", which is also placed in the datasets repository upon running. The notebook will also generate the predictions csv "xgb_tuned_log.csv", which is placed in the submissions repository.

### Libraries
1. For Data Cleanup and Feature Generation: numpy, pandas, sklearn, scipy
2. For Predictive Modeling: sklearn, xgboost
3. For Visualizations: matplotlib, seaborn, Tableau Desktop

### Run Time/Hardware
Runs in about 90 minutes on a fairly high-powered desktop (i7-4790) with 16 gb of RAM. 
