#  Employee Stay vs Quit Prediction  

> *“Predict employee turnover before it happens — and take action before it’s too late.”*  

This project aims to predict whether an employee will **stay or quit** the company using **Logistic Regression**.  
It’s part of **HR Analytics**, designed to help organizations understand *why employees leave* and *how to retain top talent*.  

---

##  Project Overview  

Every organization wants to retain skilled employees.  
Using employee data, this project uncovers **hidden patterns** behind attrition — such as satisfaction, workload, and tenure — and builds a **Logistic Regression** model that predicts who is most likely to leave.  

**Goal:**  
 Enable HR teams to make *data-driven retention decisions* instead of relying on guesswork.  

---

##  Steps Involved  

###  1. Data Cleaning  
- Removed irrelevant and duplicate columns  
- Cleansed and standardized department names  
- Stripped extra spaces from column headers  
- Converted categorical variables (like salary & department) to numeric form  

###  2. Exploratory Data Analysis (EDA)  
- Identified top drivers influencing attrition (satisfaction, workload, tenure)  
- Visualized trends using bar charts, boxplots, and heatmaps  
- Analyzed workload patterns (`Monthly Hours`, `Projects`) vs. quitting behavior  
- Checked for outliers and balanced class distribution  

###  3. Model Building  
- Performed **Train-Test Split (80–20)**  
- Applied **Feature Scaling** with `StandardScaler`  
- Trained a **Logistic Regression Model** for classification  
- Tested different thresholds for best prediction accuracy  

###  4. Model Optimization & Evaluation  
- Tuned decision threshold for optimal balance between **Precision** and **Recall**  
- Evaluated performance using:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
  - Confusion Matrix
---
 ##  Key Insights & Findings  

 **Low Satisfaction = High Attrition Risk**  
Employees with low satisfaction levels are 3x more likely to quit.  

 **Work Overload Leads to Burnout**  
Long working hours combined with poor evaluations indicate higher quitting probability.  

 **Tenure Stability**  
Employees with **3–5 years** of experience are more stable than new or long-serving employees.  

 **Optimized Threshold Boosted Recall**  
After tuning, the model balanced both false positives and false negatives effectively.  

 **Salary Levels Matter**  
Low-salary groups show the highest turnover trend — a major retention signal.  

---

##  Technologies Used  

| Category | Tools/Libraries |
|-----------|----------------|
| Programming | **Python 3.10+** |
| Data Processing | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Modeling | scikit-learn |
| Notebook Environment | Jupyter Notebook |

---
##  Business Value for the Client  

 **Retention Strategy:** Helps HR identify employees at risk and take proactive actions.  
 **Cost Savings:** Reduces hiring & onboarding costs by minimizing turnover.  
 **Decision Support:** Translates analytics into clear business insights for management.  
 **Employee Engagement:** Identifies key satisfaction levers to improve morale.  
 **Scalable Approach:** Can be extended to other predictive HR models (promotion, performance).  

---
