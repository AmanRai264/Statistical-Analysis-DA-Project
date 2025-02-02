# Statistical Analysis Data Project

## Overview
This project focuses on performing statistical analysis on a dataset to extract meaningful insights. The analysis includes data cleaning, exploratory data analysis (EDA), and various statistical techniques to understand data patterns and relationships.

## Dataset
The dataset used in this project is `train.csv`. It contains multiple features, including numerical and categorical variables. Some key columns include:
- **Age**: Processed to handle missing values and ensure numerical consistency.
- **Pclass, Sex, Fare, Survived**: Used for predictive modeling.
- **Other features**: Various attributes analyzed for insights.

## Features
- Data Cleaning: Handling missing values, type conversion, and consistency checks.
- Exploratory Data Analysis (EDA): Summary statistics, visualizations, and correlation analysis.
- Statistical Techniques: Applying statistical methods to derive insights from the data.
- Machine Learning Model: Implemented Logistic Regression to predict survival on the Titanic dataset.

## Installation
To run this project, ensure you have the following dependencies installed:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Usage
Clone the repository and run the Jupyter Notebook:

```bash
git clone <repository-url>
cd <project-folder>
jupyter notebook "Statistical Analysis DA Project.ipynb"
```
## Machine Learning Model
This project includes a Logistic Regression model trained on the Titanic dataset to predict survival probabilities. The workflow includes:
1. Loading the Titanic dataset.
2. Selecting relevant features (`Pclass`, `Sex`, `Age`, `Fare`, `Survived`).
3. Preprocessing the data (handling missing values, encoding categorical features).
4. Splitting the dataset into training and test sets.
5. Training a Logistic Regression model.
6. Evaluating model performance using accuracy score and classification report.





