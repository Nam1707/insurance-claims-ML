# Health Insurance Claims Analysis

## About the Data:

The dataset provided here contains a comprehensive set of information crucial for assessing health insurance claims. It includes factors such as age, gender, Body Mass Index (BMI), blood pressure, diabetic status, number of children, region, smoking status, and claim amounts.

## Getting Started:

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed
3. Open the Jupyter notebook provided to explore the dataset, perform data cleaning, visualization, analysis, and model training.

## Cleaning and Prepping the Dataset:

The provided Jupyter notebook walks through the process of cleaning and preparing the dataset for analysis:

- Checking for missing values and dropping them.
- Removing irrelevant columns.
- Converting categorical variables into numerical ones.
- Organizing data into meaningful groups for analysis.

## Data Visualization and Analysis:

The notebook includes various visualizations and analyses to understand the relationships between different factors and insurance claim amounts:

- Overview of the dataset statistics.
- Histograms for numerical variables (Age, BMI, Bloodpressure, and Claim).
- Pie chart and violin plot for BMI distribution and its relationship with age.
- Box plot and count plots for exploring relationships between gender, age groups, regions, and smoking status with insurance claims.
- Correlation matrices to understand the relationships between different factors.

## Model Training:

The notebook covers the training of several machine learning models to predict insurance claim amounts:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XG Boost
- K-Nearest Neighbors Regressor

The models are evaluated based on their R-squared values, adjusted R-squared values, mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE). The best performing model is then used to make price predictions.

## Technologies Used:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Altair
- Scikit-learn
- XGBoost

Feel free to explore the notebook and provide feedback or suggestions for improvement :)
