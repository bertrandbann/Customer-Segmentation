# Customer Segmentation Using Machine Learning
## Decision Tree & Random Forest Classification
### Project Overview

Customer segmentation is a critical strategy for businesses seeking to better understand their customers and tailor marketing strategies accordingly.
In this project, machine learning techniques are used to classify customers into distinct segments based on demographic and behavioural characteristics. By leveraging classification models, the analysis identifies the key factors influencing customer segmentation and evaluates the predictive performance of different algorithms.

Two machine learning models were implemented:

-Decision Tree Classifier

-Random Forest Classifier

The objective is to demonstrate how machine learning can support data-driven customer targeting, marketing optimisation, and strategic decision-making.

## Business Objective

Businesses often struggle to understand the diversity within their customer base. Without effective segmentation:

-Marketing campaigns become inefficient

-Customer engagement decreases

-Opportunities for personalised offers are missed

Customer segmentation enables companies to:

-Identify high-value customer groups

-Personalise marketing strategies

-Improve customer retention

-Optimise product recommendations

This project illustrates how machine learning models can help automate and improve customer segmentation processes.

## Dataset Description

The dataset contains demographic and behavioural attributes describing customers.

Feature	Description
Gender	Customer gender, 
Age	Customer age, 
Ever_Married	Marital status, 
Graduated	Education status, 
Profession	Occupation, 
Work_Experience	Years of professional experience, 
Spending_Score	Spending behaviour, 
Family_Size	Household size, 
Var_1	Additional categorical variable, 
Segmentation	Target variable representing customer segment

The target variable represents the customer segment each individual belongs to.

## Data Preprocessing

Before training the machine learning models, several preprocessing steps were applied.

### Handling Missing Values

Missing values were handled using SimpleImputer:

Numerical features → median imputation

Categorical features → most frequent value

### Encoding Categorical Variables

Categorical variables were converted into numerical format using:

One-Hot Encoding for predictor variables

Label Encoding for the target variable

### Feature Selection

The dataset was separated into:

Features (X) – independent variables used for prediction

Target (y) – customer segmentation label

### Train-Test Split

The dataset was split into:

80% training data

20% testing data

This allows the models to be evaluated on unseen data.

## Machine Learning Models
### Decision Tree Classifier

A Decision Tree model was implemented as the baseline classification algorithm.

Decision Trees are useful because they:

Are easy to interpret

Capture nonlinear relationships

Provide insight into feature importance

Model parameters:

Max Depth: 6

Random State: 42

### Random Forest Classifier

A Random Forest model was implemented to improve predictive performance.

Random Forest works by combining multiple decision trees to reduce overfitting and improve model generalisation.

Advantages include:

- Higher prediction stability

- Better generalisation

- Improved accuracy compared to a single tree

### Model Evaluation

The models were evaluated using standard classification metrics.

Evaluation metrics include:

Accuracy

Model comparison

Feature importance analysis

These metrics allow us to assess how effectively customer attributes predict segmentation.

## Key Insights

The analysis highlights several variables that play an important role in determining customer segments.

Potential influential features include:

- Spending behaviour

- Age

- Profession

- Work experience

- Family size

These insights can help businesses design more targeted marketing strategies and improve customer engagement.

## Technologies Used

### Programming Language

#### Python

- Libraries

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn

#### Machine Learning Techniques

- Decision Trees

- Random Forest

- Data Imputation

- Feature Encoding

- Train/Test Split
