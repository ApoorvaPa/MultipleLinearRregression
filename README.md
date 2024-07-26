WHO Life Expectancy Prediction
This repository contains code and data for predicting life expectancy using the WHO dataset. The project leverages multiple linear regression to model the relationship between life expectancy and various health, economic, and demographic indicators.

Dataset
The dataset used in this project is sourced from the World Health Organization (WHO) and includes various indicators such as adult mortality, infant deaths, alcohol consumption, expenditure on healthcare, hepatitis B immunization, BMI, under-five deaths, GDP, population, thinness, income composition, and schooling. The target variable is life expectancy.

Features
Year: Year of observation
Status: Developed or developing status of the country
Adult Mortality: Adult mortality rates per 1000 population
Infant Deaths: Number of infant deaths per 1000 population
Alcohol: Alcohol consumption per capita (liters)
Percentage Expenditure: Expenditure on healthcare as a percentage of GDP
Hepatitis B: Hepatitis B immunization coverage among 1-year-olds (%)
Measles: Number of reported measles cases per 1000 population
BMI: Average body mass index
Under-Five Deaths: Number of under-five deaths per 1000 population
Polio: Polio immunization coverage among 1-year-olds (%)
Total Expenditure: Total expenditure on health as a percentage of GDP
Diphtheria: Diphtheria immunization coverage among 1-year-olds (%)
HIV/AIDS: Deaths per 1000 live births due to HIV/AIDS (0-4 years)
GDP: Gross Domestic Product per capita (USD)
Population: Population of the country
Thinness 1-19 years: Prevalence of thinness among children and adolescents for age 1 to 19 (%)
Thinness 5-9 years: Prevalence of thinness among children for age 5 to 9 (%)
Income Composition of Resources: Human Development Index in terms of income composition
Schooling: Number of years of schooling
Preprocessing
Handling Missing Values: Imputation of missing values using the mean strategy.
One-Hot Encoding: Encoding categorical variables (e.g., 'Status') using one-hot encoding.
Model
Multiple Linear Regression: Used to predict life expectancy based on the provided features.
Results
The performance of the model is evaluated using Mean Squared Error (MSE) and R² score.

Usage
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/who-life-expectancy-prediction.git
cd who-life-expectancy-prediction
Install dependencies:

sh
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:

sh
Copy code
jupyter notebook WHO_Life_Expectancy_Prediction.ipynb
Run the Python Script:

sh
Copy code
python predict_life_expectancy.py
Conclusion
This project demonstrates the application of multiple linear regression to predict life expectancy based on a variety of health, economic, and demographic indicators. The results provide insights into the factors that significantly influence life expectancy across different countries.
