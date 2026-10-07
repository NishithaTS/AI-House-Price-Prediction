# AI-Based House Price Prediction and Exploratory Data Analysis

## Project Overview

This project focuses on analyzing housing data and predicting house prices using Data Analytics, Exploratory Data Analysis (EDA), Data Visualization, and Machine Learning techniques.

The project uses the Ames Housing dataset from Kaggle. Different housing features such as living area, overall quality, year built, garage area, and other property characteristics are analyzed to understand their relationship with house prices.

Machine learning models are then trained to predict house prices and their performance is compared using MAE, RMSE, and R² Score.

---

## Objectives

- Analyze the housing dataset.
- Perform data cleaning and preprocessing.
- Identify and handle missing values.
- Perform Exploratory Data Analysis.
- Visualize important patterns and relationships.
- Analyze factors affecting house prices.
- Build machine learning models for house price prediction.
- Compare the performance of different regression models.
- Identify the most important features influencing house prices.

---

## Dataset

**Dataset:** House Prices: Advanced Regression Techniques

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

The dataset contains information about residential properties in Ames, Iowa.

The main target variable used for prediction is:

`SalePrice`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Missing Value Analysis
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Encoding
   ↓
Train-Test Split
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Feature Importance Analysis
   ↓
House Price Prediction
```

---

## Exploratory Data Analysis

The project includes several visualizations to understand the dataset:

- Histogram of house prices
- Box plot of house prices
- Bar graph of average price by house quality
- Line chart of average price by year built
- Pie chart of house quality categories
- Correlation heatmap
- Scatter plot of living area vs house price
- Count plot of house quality
- Bubble plot of living area vs house price

These visualizations help identify patterns, trends, correlations, and potential outliers in the housing data.

---

## Data Preprocessing

The following preprocessing techniques were applied:

1. Missing values were identified.
2. Categorical missing values were replaced with `"None"`.
3. Numerical missing values were filled using the median.
4. Duplicate rows were checked and removed.
5. The `Id` column was removed from the machine learning features.
6. Categorical variables were converted into numerical form using one-hot encoding.
7. The dataset was divided into training and testing sets.

---

## Machine Learning Models

Three regression models were implemented:

### 1. Linear Regression

Used as a baseline regression model for predicting house prices.

### 2. Decision Tree Regressor

Used to capture nonlinear relationships between housing features and house prices.

### 3. Random Forest Regressor

An ensemble learning model consisting of multiple decision trees. It was used to improve prediction performance and identify important features.

---

## Model Evaluation

The models were evaluated using:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted prices.

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction error.

### R² Score

Measures how well the model explains the variation in house prices. A higher R² score indicates better performance.

---

## Feature Importance

Feature importance was calculated using the Random Forest model to identify the housing characteristics that contribute most to house price prediction.

The project visualizes the top 10 important features.

---

## Project Structure

```text
House_Price_AI_Project/
│
├── train.csv
├── NishithaT_HousePricePrediction.ipynb
├── requirements.txt
├── README.md
└── NishithaT_HousePricePrediction_ProjectReport.docx
```

---

## How to Run the Project

### Step 1: Clone or download the project

Download the complete project folder to your computer.

### Step 2: Install Python

Make sure Python 3.x is installed.

### Step 3: Install required libraries

Open Command Prompt or PowerShell inside the project folder and run:

```bash
pip install -r requirements.txt
```

### Step 4: Open Jupyter Notebook

Run:

```bash
jupyter notebook
```

### Step 5: Open the notebook

Open:

```text
NishithaT_HousePricePrediction.ipynb
```

### Step 6: Run the cells

Run the notebook cells from top to bottom.

Make sure `train.csv` is present in the same folder as the notebook.

---

## Results

The project compares Linear Regression, Decision Tree Regression, and Random Forest Regression using MAE, RMSE, and R² Score.

The model with the highest R² Score is selected as the best-performing model.

The project also provides:

- Actual vs predicted price comparison
- Prediction error analysis
- Feature importance analysis
- House price visualizations
- Data-driven insights

---

## Key Insights

The analysis helps understand how different property characteristics influence house prices.

Important factors such as overall house quality, living area, garage characteristics, and other property features can have a significant relationship with the final sale price.

Machine learning provides a data-driven approach for estimating house prices based on available property characteristics.

---

## Conclusion

This project demonstrates how Data Analytics and Artificial Intelligence can be combined to solve a real-world house price prediction problem.

The complete workflow covers data preprocessing, exploratory analysis, visualization, machine learning, model evaluation, and feature importance analysis.

The project provides a practical example of using Python and machine learning techniques to extract meaningful insights from real-world housing data and develop a predictive model.

---

## Author

**Nishitha T S**

B.Tech Computer Science and Engineering

AI/ML | Data Analytics | Generative AI | Full-Stack Development