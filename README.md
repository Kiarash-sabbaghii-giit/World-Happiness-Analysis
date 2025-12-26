# World-Happiness-Analysis
A data science project analyzing global happiness trends (2015–2019) using descriptive, predictive, and prescriptive analytics.
# World Happiness Analysis (2015–2019)

## 📌 Overview
This project presents an end-to-end data science analysis of the World Happiness Report from 2015 to 2019.  
The objective is to understand the key drivers of happiness across countries using descriptive, diagnostic, predictive, and prescriptive analytics, and to translate data insights into actionable policy recommendations.

---

## 📊 Dataset
- **Source:** World Happiness Report
- **Years Covered:** 2015–2019
- **Observations:** Country-level data
- **Final Dataset:** A cleaned and standardized dataset combining all five years

### Key Variables
- Happiness Score
- GDP per capita
- Social Support
- Healthy Life Expectancy
- Freedom
- Generosity
- Perceptions of Corruption
- Region
- Year

---

## 🧹 Data Preparation
The project includes a complete data preparation pipeline:
- Inspection of each yearly dataset
- Column standardization across different file formats
- Data type corrections
- Handling missing values
- Outlier analysis and treatment
- Merging all datasets into a single analytical table

All steps are fully documented in the Jupyter Notebook to ensure reproducibility.

---

## 🔍 Exploratory & Diagnostic Analysis
Key exploratory questions addressed:
- How does average happiness change over time?
- Which countries rank highest and lowest each year?
- How do GDP per capita and social support evolve from 2015 to 2019?
- Which variables are most strongly correlated with happiness?

Correlation analysis and visualizations were used to identify the most influential factors.

---

## 🤖 Predictive Modeling
A multiple linear regression model was developed to predict happiness scores based on socio-economic factors.

- **Model Type:** Multiple Linear Regression
- **Features:** GDP per capita, social support, health, freedom, generosity, corruption
- **Evaluation Metric:** R² and RMSE
- **Key Result:**  
  - R² ≈ 0.71 (random split)  
  - R² ≈ 0.73 when predicting 2019 using only 2015–2018 data  

This demonstrates strong generalization and temporal stability.

---

## 🧠 Prescriptive Analysis
Scenario-based analysis was conducted to support decision-making:
- Impact of increasing GDP and social support by 10%
- Comparison of policy strategies for low-happiness countries
- Evaluation of reducing corruption versus increasing generosity

The analysis shows that balanced economic growth, strong social support, and improved health outcomes yield the highest and most sustainable gains in happiness.

---

## 🧾 Key Insights
- GDP per capita is the strongest predictor of happiness
- Social support can partially compensate for lower income levels
- Reducing corruption has a greater long-term impact than increasing generosity
- Social and health policies are critical for sustainable well-being

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure
