# Machine Learning Final Project
NYCU CS_CS20024 Machine Learning 
### Introduction
The task of the final project was to predict the product failure using the [Tabular Playground Series](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview) from kaggle. The dataset contains much noise and missing values, therefore, I utilized several data preprocessing skills to improve the accuracy. Logistic regression model was used to predict the  probability of product failure.
### How to reproduce the result
1. Download [requirements.txt](https://github.com/sheepycat/NYCU_ML_final_project/blob/main/requirements.txt), [109550134_Final_inference.ipynb](https://github.com/sheepycat/NYCU_ML_final_project/blob/main/109550134_Final_inference.ipynb), [trained_model.joblib](https://github.com/sheepycat/NYCU_ML_final_project/blob/main/trained_model.joblib)
2. Rebuild environment using requirements.txt:

    ```sh
    pip install -r requirements.txt
    ```
3. Modify the paths in 109550134_Final_inference.ipynb
4. Execute 109550134_Final_inference.ipynb to get the result: submission.csv

