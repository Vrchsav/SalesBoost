# SalesBoost



# Big Mart Sales Prediction Project

This project focuses on predicting sales for Big Mart outlets using machine learning techniques, specifically employing the XGBoost regression model. The prediction is based on a dataset containing various features related to products and outlets.

## Project Overview

The notebook demonstrates the following key steps:

1. **Data Loading**: Importing the dataset from a CSV file into a Pandas DataFrame.
2. **Data Exploration**: Initial exploration to understand the dataset structure and inspect the first few records.
3. **Data Preprocessing**: Addressing missing values and encoding categorical variables to prepare the data for modeling.
4. **Model Training**: Implementing an XGBoost regression model to predict the `Item_Outlet_Sales`.
5. **Model Evaluation**: Using appropriate metrics to evaluate the model's performance and accuracy.

## Dataset

The dataset, `Train.csv`, contains 8,523 entries with the following features:

- **Item_Identifier**: Unique product ID
- **Item_Weight**: Weight of the product
- **Item_Fat_Content**: Categorical variable describing the fat content of the product
- **Item_Visibility**: The percentage of total display area of all products in a store allocated to this particular product
- **Item_Type**: The category to which the product belongs
- **Item_MRP**: Maximum Retail Price (list price) of the product
- **Outlet_Identifier**: Unique store ID
- **Outlet_Establishment_Year**: The year the outlet was established
- **Outlet_Size**: The size of the store
- **Outlet_Location_Type**: The type of location in which the store is located
- **Outlet_Type**: The type of outlet
- **Item_Outlet_Sales**: Sales of the product in the particular store (target variable)

## Prerequisites

Ensure you have Python installed along with the following libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

You can install these using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

## Running the Project

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Vrchsav/SalesBoost.git
   ```

2. Navigate to the project directory:

   ```bash
   cd SalesBoost
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the `sales_prediction.ipynb` file and run each cell sequentially to execute the code.

## Key Steps in the Notebook

- **Data Preprocessing**: Handle missing values for `Item_Weight` using the mean and for `Outlet_Size` using the mode.
- **Exploratory Data Analysis (EDA)**: Visualize the data distribution and relationships using `matplotlib` and `seaborn`.
- **Model Implementation**: Train an XGBoost regressor on the preprocessed data.
- **Evaluation**: Assess model performance using metrics such as RMSE and R-squared.

## Results

The model's performance is evaluated based on its ability to accurately predict sales figures, providing insights into feature importance and data trends.


## Acknowledgments

- The dataset is sourced from Big Mart.
- The XGBoost library is utilized for its efficient implementation of gradient boosting.


