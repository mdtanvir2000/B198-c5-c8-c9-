# **End-to-End Data Science Project: Predicting Technological Developments in IKEA's Furniture Prices**

## **Project Overview**
This repository contains the implementation of an end-to-end data science project focused on predicting the price of IKEA furniture products based on various attributes like category, dimensions, designer, and more. The project uses machine learning algorithms such as **Linear Regression**, **Random Forest**, and **XGBoost** to predict the prices of furniture items in a dataset obtained from IKEA's web scrapings.

## **Repository Structure**
The project is organized into the following directory structure:

## **Project Description**
The objective of this project is to predict the price of IKEA furniture based on various features, such as:
- `item_id`: Unique identifier for each product
- `category`: Type of furniture (e.g., Beds, Chairs, etc.)
- `price`: The target variable to predict
- `depth`, `height`, `width`: Dimensions of the furniture
- `designer`: Designer of the furniture item
- `old_price`: Previous price of the item

The dataset was preprocessed by handling missing values, removing outliers, and encoding categorical variables for use in machine learning models. The project uses multiple regression models to predict prices, and their performance is evaluated using metrics like **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared (R²)**.

## **Steps Involved**
1. **Data Cleaning**: The raw dataset was cleaned by handling missing values, filling numeric columns with their mean, and categorical columns with the most frequent value.
2. **Outlier Removal**: Outliers in the `price` column were detected and removed using the Interquartile Range (IQR) method.
3. **Feature Engineering**: Categorical variables were one-hot encoded to make them suitable for machine learning models.
4. **Model Building**: Regression models including **Linear Regression**, **Random Forest**, and **XGBoost** were trained on the data.
5. **Model Evaluation**: The models' performances were compared using evaluation metrics like MAE, MSE, and R².

## **Installation and Setup**
To run this project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mdtanvir2000/B198-c5-c8-c9-.git
   cd B198-c5-c8-c9-

2. **Install dependencies:**:
   ```bash
   pip install -r requirements.txt

**Dependencies**
The following Python libraries are required to run the project:

1. `pandas`: For data manipulation and analysis
2. `numpy`: For numerical operations
3. `matplotlib, seaborn`: For data visualization
4. `sklearn`: For machine learning models and preprocessing
5. `xgboost`: For XGBoost models

**Usage**
1. Preprocessing and Model Building:
The Jupyter notebook B198(c5_c8_c9).ipynb contains all steps for preprocessing, model training, and evaluation.
The notebook also visualizes data at key points, such as missing values, outliers, and model performance.

**Running the Code:**
You can execute the code step-by-step in the Jupyter notebook.

## **Model Evaluation:**
The model evaluation results contains metrics like:

1. Mean Absolute Error (MAE)
2. Mean Squared Error (MSE)
3. R² Score

## **Conclusion**
This project demonstrates a basic end-to-end workflow for building a regression model to predict product prices based on available features. The performance of multiple machine learning models was evaluated and compared to identify the most accurate model for this problem.
