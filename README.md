# USING-DENTAL-METRICS-TO-PREDICT-GENDER
Capstone Project [USING DENTAL METRICS TO PREDICT GENDER]
## Project Overview
This project utilizes dental measurements to predict an individual's gender. It addresses challenges in forensic dentistry, particularly in identifying gender in cases where conventional methods are not feasible, such as during natural calamities or when dealing with skeletal remains.

### Objective
The primary goal is to analyze dental data and build machine learning models that predict gender based on a combination of dental metrics.

---

## Background and Scope
Forensic dentistry is a crucial branch of forensic medicine. Teeth and bones are among the last to decay, making them reliable sources of information for gender identification. This project aims to leverage this data scientifically and systematically.

---

## Project Workflow
1. *Raw Data Collection*
2. *Data Preprocessing*
   - Handling Missing Values
   - Encoding Categorical Data
   - Normalization
3. *Exploratory Data Analysis (EDA)*
   - Visualizations and Correlation Analysis
   - Outlier Detection
4. *Model Building*
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - XGBoost Classifier
5. *Evaluation*
   - Confusion Matrix
   - ROC and AUC Curves
6. *Documentation and Reporting*

---

## Dataset Information
- *Target Variable*: Gender (Male/Female)
- *Independent Variables*: 
  - Inter-canine distances (intraoral and casts)
  - Right and left canine casts
  - Other dental measurements
- *Additional Attributes*: SampleID, SL No., and Age

---

## Libraries and Tools Used
- *Python Libraries*:
  - pandas for data manipulation
  - numpy for mathematical operations
  - matplotlib and seaborn for data visualization
  - scikit-learn for preprocessing and model building
- *Platform*: Jupyter Notebook

---

## Key Steps in Implementation
1. Import necessary libraries.
2. Load and preprocess the dataset.
3. Perform EDA to understand relationships between variables.
4. Build predictive models using multiple machine learning algorithms.
5. Evaluate models using metrics such as accuracy, confusion matrix, and AUC.

---

## Results
The best-performing model achieved high accuracy in predicting gender based on dental metrics. The results demonstrated the potential of machine learning in forensic dentistry applications.

