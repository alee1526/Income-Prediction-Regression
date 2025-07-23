# Income-Prediction-Using-Regression

This project applies regression techniques to predict labor income for individuals in dependent employment in Uruguay, based on socioeconomic data. Through detailed analysis and machine learning models, the target variable `ysos_dep` (income from dependent employment) is estimated with a focus on accuracy and interpretability.

## Objective
The goal is to develop a predictive model that estimates labor income based on features such as age, education, and occupation, using linear regression and advanced methods like Ridge and Lasso to optimize results.

## Dataset
The data comes from the 2017 Continuous Household Survey (ECH) provided by Uruguay's National Institute of Statistics (INE). This dataset includes key information about the socioeconomic conditions of Uruguayan households.

Source: INE - ECH 2017

## Techniques Applied
Various regression techniques were employed to achieve the objective:

- Linear Regression: Foundation for modeling relationships between variables.
- Ridge and Lasso: Regularization methods to enhance generalization and select relevant features.
- Exploratory data analysis and preprocessing to ensure data quality.

## Key Results
The final model identifies critical factors influencing income, such as education and occupation type, achieving a balance between accuracy and simplicity through regularization.
How to Explore the Project
The complete analysis is available in the repository's notebook, which presents the data, models, and results in a structured manner. To run it, ensure you have the required libraries (pandas, scikit-learn, etc.) and the data file `P_2017_Terceros.sav`.

## Credits

Data: National Institute of Statistics (INE) of Uruguay.
Developed as part of the Machine Learning Techniques course, Master in Big Data ORT Uruguay, Semester 1 - 2025.
