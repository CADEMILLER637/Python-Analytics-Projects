# Python Analytics Projects — Cade Miller
Business Analytics, Northern Arizona University (Class of 2027)

Python data analysis and machine learning projects completed in 
ISM 370 and BAN 440 at NAU. Each project applies a different 
technique to a real-world business dataset and concludes with 
an actionable business recommendation.

---

## Projects

### Bank Marketing Subscription Classifier
**Tools:** Python, RapidMiner AI Studio (scikit-learn, pandas)  
**File:** `bank_marketing_classification.ipynb`

Compared Decision Tree and K-NN classification models on a 
4,311-record imbalanced dataset (88.5% majority class) to predict 
which bank clients would subscribe to a term deposit.

Key finding: K-NN achieved 88.48% accuracy by predicting "No" 
for every single record — never identifying a single subscriber. 
The Decision Tree's lower accuracy was far more valuable because 
it actually identified true positives. Demonstrated why confusion 
matrices and precision/recall matter more than raw accuracy on 
imbalanced datasets.

Business recommendation: Deploy the Decision Tree as a 
pre-campaign scoring tool to prioritize outreach toward 
high-probability subscribers, reducing call volume and 
improving conversion rates.

---

### Insurance Charges Regression Model
**Tools:** Python (statsmodels, pandas, seaborn)  
**File:** `insurance_charges_ols_regression.ipynb`

Built an OLS multiple regression model to predict medical 
insurance charges using age, BMI, smoking status, region, 
and number of dependents.

Key finding: Engineered a BMI × smoker interaction term that 
significantly improved model fit — the cost impact of BMI is 
compounded for smokers, not simply additive. Interpreted the 
full model summary and generated cost predictions for new 
patient profiles.

Business recommendation: Use interaction-aware pricing models 
for risk-based insurance segmentation rather than treating 
BMI and smoking as independent factors.

---

### DC Bike Share Exploratory Data Analysis
**Tools:** Python (pandas, matplotlib)  
**File:** `dc_bikeshare_eda.ipynb`

Exploratory analysis of hourly bike share ridership patterns 
in Washington D.C., comparing 2011 and 2012 usage trends.

Key finding: Identified significant downtime periods with near-zero 
ridership alongside peak demand windows. Grouped median ridership 
by month for both years to surface seasonal demand patterns and 
year-over-year growth.

---

### Tips Dataset Regression Analysis
**Tools:** Python (statsmodels, seaborn)  
**File:** `tips_regression_analysis.ipynb`

Regression and distribution analysis on restaurant tipping 
behavior across gender, party size, time of day, and total 
bill amount.

---

## Skills Demonstrated
- Supervised machine learning (classification, regression)
- Model evaluation: confusion matrix, precision/recall, accuracy
- Feature engineering and interaction terms
- Handling class imbalance
- Exploratory data analysis and visualization
- Business interpretation of statistical outputs

---

## Tools
Python · pandas · scikit-learn · statsmodels · seaborn · 
matplotlib · RapidMiner AI Studio
