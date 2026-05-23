# 💊 FDA Drug Adverse Event Reports (2015–2026) | Classification Modeling

## 📌 Project Overview
This project focuses on building predictive classification models using the **FDA Adverse Event Reporting System (FAERS)** dataset, covering reported drug side effects and critical medical events from **2015 to 2026**. 

FAERS is a cornerstone public pharmacovigilance database used to monitor post-market medication safety. By leveraging machine learning architectures, this project uncovers hidden clinical patterns, extracts risk factors, and predicts severe clinical outcomes based on patient demographics, drug profiles, and reporting channels.

---

## 🎯 Objectives & Targeted Predictions
The main goal is to build an end-to-end machine learning classification pipeline capable of isolating high-risk patient-drug cohorts and predicting critical safety metrics:
* **Outcome Severity:** Classifying whether an adverse reaction leads to a `serious` case flag, `is_hospitalized`, or results in an `is_fatal` outcome.
* **Feature Relationship Mapping:** Measuring how demographics, reporting sources, and drug configurations dictate case escalations.

---

## 🏗️ Technical Pipeline & Stack
* **Language:** Python
* **Data Processing & Engineering:** Pandas, NumPy, Scikit-learn
* **Machine Learning Architectures:** LightGBM, XGBoost, Random Forest (Ensemble Classifiers)
* **Visualization & Diagnostics:** Matplotlib, Seaborn (ROC/AUC analysis, Feature Importance plots, Confusion Matrices)

### Key Engineering Strategies Implemented:
1. **Handling Pervasive Data Gaps:** Managed severe reporting omissions, such as addressing the missing 72% block of patient weight records by using feature isolation methods to avoid toxicity measurement distortions.
2. **Bias Mitigation:** Controlled for extreme over-representation patterns (such as US-centric reporting dominating 60% of the dataset).
3. **Optimized Loss Functions:** Fine-tuned ensemble classification algorithms to prioritize precision-recall curves, reducing false-negative instances for high-stakes healthcare scenarios.

---

## 📊 Core Insights & Constraints Handled
* **Reporting Constraints:** Addressed the artificial annual stratification cap of exactly 48,000 records per year to ensure historical trends (outside of anomalous events like the COVID-19 timeline) did not corrupt model predictions.
* **Label Noise Remediation:** Accounted for subjective diagnostic variations where fatality tracking depends strictly on voluntary reporter assessments rather than official death certifications.

---

## 🛠️ Local Implementation

To run this notebook and reproduce the classification benchmarks, initialize your environment within this directory:

```bash
# Navigate to the project directory
cd FDA-Drug-Adverse-Event-Classification

# Initialize virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install requirements
pip install -r requirements.txt
