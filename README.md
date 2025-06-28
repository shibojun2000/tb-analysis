
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TB-ANALYSIS</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to TB-ANALYSIS</h1>
  </header>
  <main>
    <p>This is a data analysis project for CIND820. </p>
    <P>The global trends in tuberculosis data might reveal some surprising correlations between economic indicators and health outcomes. This dataset is ideal for policymakers, researchers, and data analysts aiming to study TB trends, evaluate healthcare interventions, and develop predictive models for disease control. </p>
    <p>Dataset used: Tuberculosis Trend. 
     <a href="https://www.kaggle.com/datasets/khushikyad001/tuberculosis-trends-global-and-regional-insights/data" target="_blank">Dataset click here </a></p>
    <p>EDA report:
     <a href="file:///C:/Users/16476/OneDrive/Desktop/Bobo/CIND820%20PROJECT/tb_eda_report.html" target="_blank"> click here </a></p>

## Tools used
- Python on Google Colab, for data cleaning, data analysis and creating report.

## Data Cleaning and Preparation
- Standardize categorical values to ensure consistent formatting of categories. 
- Check for any outliers (eg. boxplot) or wrong values.
- Check for date consistency. 
- Check for equality in categories. 

## Research Quesions
1. How have TB incidence and mortality rates evolved over time across different income levels and world regions?
2.	Which socioeconomic, health, and demographic factors are the most important predictors of TB incidence rate across countries and years?" 
3.	Do countries with higher BCG vaccination coverage have lower TB mortality rates, after controlling for health and socioeconomic factors? 

## Project Approach
1.	Data Cleaning and Preprocessing.
2.	EDA (Exploratory Data Analysis) that create visualizations to show relationships between attributes.
3.	Research Questions and Analytical Techniques:
    -	For RQ1:
        -	Will group data by ‘year’ and ‘income_level’ / ‘region’.
        -	Use linear regression within each group to quantify trends.
        -	Apply ANOVA to test whether trends differ significantly by income level or region.
        -	Evaluate by using visualization patterns and R-Square/ p-values from linear models.
    -	For RQ2:
        -	Select potential predictors from the attributes.
        -	Train model using multiple linear regression.
        -	Perform feature scaling.
        -	Evaluate by using R-Square/ p-values for model performance and feature importance ranking.
    -	For RQ3:
        -	Use multiple linear regression with dependent variable ‘TB_Mortality_Rate’, and independent variables such as ‘BCG_Vaccination_Coverage’, ‘Health_Expenditure_Per_Capita’, ‘GDP_Per_Capita’ etc.
        -	Evaluate by using R-Square/ p-values and comparing models with and without ‘BCG_Vaccination_Coverage’.
4.	Use train-test split and cross-validation and evaluate models by using R-Squre etc.
5.	Interpret the result and discuss limitations.


    
  </main>


  <footer>
    <p>&copy; 2025 BOJUN S.</p>
  </footer>
</body>
</html>
