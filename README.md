### Reducing Urban Poverty Through Economic Data Analysis

The project "Reducing Urban Poverty through Economic Data Analysis" aims to address the critical issue of urban poverty, which aligns with the Sustainable Development Goals (SDGs). By analyzing economic data, this project seeks to uncover insights that can inform policy and decision-making to alleviate poverty.

### Project Objectives
The primary objectives of this project are:
- To predict socio-economic indicators that influence urban poverty.
- To develop a machine learning model that can accurately forecast these indicators.
- To provide actionable insights that can aid in policy formulation and intervention strategies.

### Data Collection

The dataset used in this project is sourced from various economic reports and databases, including the World Bank. It includes multiple socio-economic indicators such as region, PPP survey year, household survey data, lending categories, and national accounts base year.
### Data Preprocessing

The dataset underwent preprocessing steps to handle missing values, outliers, and to normalize the data for analysis.

## Exploratory Data Analysis (EDA) and Feature Engineering

EDA involved visualizing the distribution of socio-economic indicators and identifying patterns and correlations. Feature engineering included creating new features like 'Income_Group_vs_Region' to enhance the predictive power of the model. Data scaling and encoding were also performed to prepare the data for machine learning algorithms.

## Model Selection and Training

### Model Evaluation and Hyperparameter Tuning

Various models were evaluated, including Support Vector Classifier (SVC), RandomForestClassifier, and Linear Regression. Hyperparameter tuning was performed using grid search and cross-validation to optimize model performance.

### Model Refinement and Testing

The models were trained on the cleaned dataset, and their performance was evaluated using metrics like Mean Squared Error (MSE) and R² score for Linear Regression, and accuracy for SVC and Random Forest. Cross-validation was used to ensure the models' robustness.

## Results

The final models demonstrated high accuracy and reliability in predicting socio-economic indicators. The RandomForest model's feature importance analysis provided valuable insights into the most influential factors affecting urban poverty.

## Deployment

The model was deployed using Gradio, providing an interactive interface for users to input socio-economic indicators and receive predictions. This interface makes the model accessible for real-world applications and decision-making.

### Recommendations:

Provide data-driven recommendations to policymakers and stakeholders to address urban poverty.

Installation

To run this project, you need to have Python installed along with the following packages:

pandas
numpy
seaborn
matplotlib
You can install these packages using pip:

pip install pandas numpy seaborn matplotlib

Clone this repository:

git https://github.com/OsamahSharaf/Reducing-Urban-Poverty-Through-Economic-Data-Analysis/tree/main

Project Structure

Acknowledgements

The data used in this project is sourced from https://www.kaggle.com/datasets/theworldbank/poverty-and-equity-database.

Matplotlib and Seaborn for providing excellent visualization tools.
