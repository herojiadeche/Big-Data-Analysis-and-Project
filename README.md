# Big Data Analysis and Project
This README can help reproduce the study.

 1. Please click the link to download and install Python: https://www.python.org/downloads/.
 
 2. Please click the link to download and install Anaconda, and install Jupyter Notebook through Anaconda: https://docs.jupyter.org/en/latest/install/notebook-classic.html.
 
 3. Please click the link to set environment in Anaconda: https://www.anaconda.com/docs/tools/working-with-conda/environments.
 
 4. Please click the link to install libraries in Jupyter Notebook: https://saturncloud.io/blog/how-to-add-a-library-in-jupyter-notebook-online/.
 
 5. The following libaraies should be installed before run the code: pandas, numpy, matplotlib, sklearn, seaborn.
 
 6. Please download all files in this GitHub repository. 
 
 7. 'WorldBankJP' folder includes the following datasets:
    - Age dependency ratio.csv
    - Inflation (CPI).csv
    - GDP growth.csv
    - GDP per capita (constant LCU).csv
    - Net migration.csv
    - Population.csv
    - Unemployment.csv
    
 8. Because of GitHub’s file size limitation, 'All_prefectures_buildings_with_migration.csv' is not included in this repository. Please download it directly from Kaggle: https://www.kaggle.com/datasets/brianmcgloughlin/japanese-housing-prices-2005-2024. This is the main dataset used in this study.
 
 9. Please open Anaconda, click Jupyter Notebook. Then find 'data_preparation.ipynb' file in your own computer. Please run the code for data preparation. It will produce the three csv files for further steps:
     - kanto_house_price_cleaned_2014_2023.csv
     - japan_indicators_filtered.csv
     - kanto_house_price_with_indicators.csv (the final combined dataset)
 
 10. Please open 'tokyo_house_model.ipynb' file in your own computer, then run the code. It includes all steps from data cleaning to SHAP analysis visualisation.
 
