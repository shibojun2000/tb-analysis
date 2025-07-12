
# 🧪 Global Tuberculosis Data Analysis Project

This project for Data Analysis Project course CIND820 with TMU explores global trends and predictors of Tuberculosis (TB) from 2000 to 2024, using a dataset compiled from Kaggle. The analysis aims to answer three primary research questions related to TB incidence, mortality, and its relationship with socioeconomic and health indicators.

---

## 🔍 Research Questions

1. **How have TB incidence and mortality rates evolved over time across different income levels and regions?**
2. **Which socioeconomic, health, and demographic factors are the most important predictors of TB incidence rate across countries and years?**
3. **Do countries with higher BCG vaccination coverage have lower TB mortality rates, after controlling for health and socioeconomic factors?**

---

## 📂 Repository Structure

```
📁 TB_Project/
│
├── 📄 README.md                 # Project summary and structure (this file)
├── 📄 tb_eda_Report.html        # Automatically generated exploratory data analysis report
├── 📄 Tuberculosis_Trends.csv   # TB dataset used in the analysis
├── 📄 CIND820_PROJECT.ipynb     # Codes and analysis on google colab

```

---

## 📊 Project Stages

1. **Data Import & Cleaning**  
   - Load CSV, check for missing values, standardize formatting.

2. **Exploratory Data Analysis (EDA)**  
   - Generate a full profiling report to understand distributions and variable types.

3. **Modeling by Research Question**
   - **RQ1:** Grouped regression and ANOVA by year, income level, and region.
   - **RQ2:** Multiple linear regression to identify top predictors of TB incidence.
   - **RQ3:** Regression analysis controlling for multiple factors to assess BCG effectiveness.

4. **Evaluation**
   - Use R-squared, p-values to evaluate model fit and significance.
   - Visualizations for trends and comparisons.

5. **Reporting**
   - Results interpreted and summarized for each research question.
   - Limitations discussed and future work suggested.

---

## 🛠️ Tools & Libraries Used

- Python (Pandas, NumPy, Seaborn, Scikit-learn, Statsmodels)
- Google Colab 
- ydata-profiling for EDA report
- GitHub for version control and sharing

---

## 🧠 Limitations

- Lack of age-specific or gender-specific individual-level data.
- Models assume linearity; more complex methods could improve insights.
- The dataset is synthetic and may not represent the actual world.

---


