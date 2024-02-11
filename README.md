# Flight Price Prediction - Exploratory Data Analysis (EDA)

This repository contains the code and analysis for performing Exploratory Data Analysis (EDA) on a dataset for flight price prediction. In this README, I'll outline the steps taken during the EDA process and provide an overview of the dataset.

## Dataset Overview
The dataset used for this analysis contains information about various flights including their prices, departure and arrival locations, date of journey, duration of flight, and other relevant features. This dataset will be used to train a machine learning model to predict flight prices.

## EDA Steps
1. **Data Loading:** The first step involved loading the dataset into a suitable data structure, such as a pandas DataFrame, using appropriate libraries like pandas in Python.

2. **Data Cleaning:** The dataset was inspected for missing values, duplicates, and inconsistencies. Missing values were either imputed or dropped based on their relevance to the analysis. Duplicates were removed to ensure the integrity of the data.

3. **Feature Engineering:** This step involved creating new features or modifying existing ones to extract more relevant information for the prediction task. Some common feature engineering techniques include extracting date-related features, encoding categorical variables, and scaling numerical features.

4. **Exploratory Data Analysis:** Various statistical techniques and visualizations were employed to explore the relationships between different features and the target variable (flight prices). This included summary statistics, distribution plots, correlation analysis, and scatter plots.

5. **Feature Selection:** Based on the insights gained from the EDA, a subset of features was selected for further analysis and model training. Feature selection helps in improving the efficiency of the model by focusing on the most relevant features.

6. **Outlier Detection and Treatment:** Outliers were identified using statistical methods or visualization techniques and appropriate actions were taken to handle them, such as removing outliers or transforming the data.

7. **Final Data Preparation:** After completing the above steps, the final dataset was prepared for model training. This involved splitting the data into training and testing sets, scaling numerical features, and encoding categorical variables.

## Repository Structure
- `data/`: This directory contains the dataset used for analysis.
- `notebooks/`: This directory contains Jupyter notebooks with the EDA code and analysis.
- `README.md`: This file provides an overview of the repository and instructions for running the code.

## Usage
1. Clone the repository to your local machine.
2. Navigate to the `notebooks/` directory.
3. Open the Jupyter notebooks in your preferred environment.
4. Follow along with the code and analysis provided in the notebooks.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn


