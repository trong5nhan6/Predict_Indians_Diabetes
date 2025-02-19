# Predict_Indians_Diabetes

## Overview

This project focuses on predicting diabetes using various machine learning models, including Logistic Regression (LG), Decision Trees (DT), Random Forests (RF), XGBoost (XGB), Multi-Layer Perceptron (MLP), and a Stacking ensemble method. The project explores the impact of Exploratory Data Analysis (EDA) on model performance by comparing results with and without EDA.

## Dataset

The dataset used in this project is the Pima Indians Diabetes Database, which can be accessed from  [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data). It contains diagnostic measurements and a binary outcome indicating the presence or absence of diabetes.

## Project Structure
    
-   `Predict_with_EDA.ipynb`: Jupyter notebook for predicting diabetes using models with EDA.
    
-   `Predict_without_EDA.ipynb`: Jupyter notebook for predicting diabetes using models without EDA.
    
-   `predict_with_MLP.ipynb`: Jupyter notebook focusing on diabetes prediction using the MLP model.
    
-   `dataset/`: Directory containing the dataset files.
        
-   `README.md`: This file, providing an overview of the project.
    

## Models Used

-   **Logistic Regression (LG)**: A linear model for binary classification.
    
-   **Decision Trees (DT)**: A non-parametric supervised learning method.
    
-   **Random Forests (RF)**: An ensemble method using multiple decision trees.
    
-   **XGBoost (XGB)**: An optimized distributed gradient boosting library.
    
-   **Multi-Layer Perceptron (MLP)**: A class of feedforward artificial neural network.
    
-   **Stacking**: An ensemble technique combining multiple models.
    

## Usage

1.  **Clone the repository**:

>     git clone https://github.com/trong5nhan6/Predict_Indians_Diabetes.git
>     cd Predict_Indians_Diabetes

    
2.  **Install dependencies**:  
    Ensure you have Python installed and evironmetn to run the notebooks.
        
3.  **Run the notebooks**:
    
    -   Open  `EDA_data.ipynb`  to perform exploratory data analysis.
        
    -   Use  `Predict_with_EDA.ipynb`  and  `Predict_without_EDA.ipynb`  to compare model performance with and without EDA.
        
    -   Explore  `predict_with_MLP.ipynb`  for specific insights using the MLP model.
        

## Results

The project aims to compare the performance of different models with and without EDA to understand the impact of data preprocessing on predictive accuracy. Detailed results and comparisons can be found in the respective notebooks.