# 📊 Data Science & Predictive Analytics Portfolio

Welcome to my data science and predictive modeling repository. This portfolio contains end-to-end data pipelines, exploratory data analysis (EDA), key performance indicator (KPI) architectures, and machine learning models designed to solve complex business intelligence challenges.

---

## 📂 Portfolio Projects

### 1. 🛍️ Olist Brazilian E-Commerce Executive Performance Report
* **Directory:** [`/Olist-ECommerce-BI`](./Olist-ECommerce-BI/)
* **Stack:** Power BI, DAX Architecture, Star Schema Data Modeling, Python, Pandas, Jupyter Notebooks
* **Core Results:** Engineered an end-to-end business intelligence ecosystem tracking ~100,000 transaction histories. Designed a production-grade data cleaning, outlier scaling, and multi-table join pipeline in Python to structure an optimized Power BI Star Schema. Built custom DAX KPI models evaluating executive operational health indicators—including Revenue vs. Goal ($863.57K vs $1.18M), On-Time Delivery Rate (92.18%), and Customer Positive Sentiment (78.11%)—complemented by a 4-page diagnostic dashboard and a formal strategic analysis report.

### 2. 👥 Customer Churn Analysis & Retention Strategy
* **Directory:** [`/Customer-Churn-Analysis`](./Customer-Churn-Analysis/)
* **Stack:** Python, Pandas, NumPy, Seaborn, Matplotlib, EDA, KPI Design
* **Core Results:** Engineered an advanced data validation pipeline to merge fragmented customer activity and support logs. Identified a stark 41% churn rate within free-tier profiles compared to a ~23% subscription baseline. Developed the predictive metric `30-Day Zero-Activity Rate` to capture drop-off indicators before they happen, giving stakeholders actionable remediation playbooks.

### 3. 🚗 Used Car Market Price Prediction Model
* **Directory:** [`/Used-Car-Price-Prediction`](./Used-Car-Price-Prediction/)
* **Stack:** Python, Scikit-learn, Random Forest, KNN Imputation, Regression Modeling
* **Core Results:** Built a comprehensive machine learning regression pipeline matching over 371,000 automotive listings. Addressed extreme value variance using robust algorithmic scaling and missing value feature fields via KNN Imputation. Deployed an optimized Random Forest architecture achieving an $R^2$ score of 88%, validating that vehicle mileage and registration cohorts dictate over 70% of asset depreciation curves.

### 4. 💊 FDA Drug Adverse Event Classification Modeling
* **Directory:** [`/FDA Drug Adverse Event Classification Modeling`](./FDA%20Drug%20Adverse%20Event%20Classification%20Modeling/)
* **Stack:** Python, Pandas, NumPy, Scikit-learn, LightGBM/XGBoost, Classification Pipelines, Hyperparameter Tuning
* **Core Results:** Developed a comprehensive machine learning pipeline using a decade of pharmacovigilance data from the FDA Adverse Event Reporting System (FAERS). Implemented advanced data processing strategies to mitigate missing value challenges—such as missing patient weight—and managed reporting biases. Built and optimized classification models predicting severe patient outcomes, including serious case flags, hospitalizations, and fatalities, utilizing demographics, report sources, and drug characteristics to improve safety-risk forecasting.

---

## 🛠️ Environment Configuration

To execute these workbooks locally, initialize a virtual environment and load dependencies inside your chosen project subfolder:

```bash
# Clone the portfolio
git clone [https://github.com/Ahmed-Shehab-Source/Data-Science-Portfolio.git](https://github.com/Ahmed-Shehab-Source/Data-Science-Portfolio.git)
cd Data-Science-Portfolio

# Navigate to a project folder
cd FDA-Drug-Adverse-Event-Classification
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```
---
## 💼 Technical Competencies
Programming & Systems: Python (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM), SQL, Markdown

Data Engineering: Classification Frameworks, Multivariate Imputation (KNN), Robust Outlier Scaling, Multi-Source Log Aggregation

Statistical Visualization: Seaborn, Matplotlib, ROC/AUC Curves, Funnel Decay Plots, Feature Importance Modeling

Domain Focus: Pharmacovigilance Analytics, Public Health Risk Assessment, Business Intelligence, Predictive Market Modelin
