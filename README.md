# 🎓 Internship Portfolio: Student Churn Analysis

This repository contains the deliverables from my internship project, 
where I analyzed student engagement and churn patterns using the 
**SLU Opportunity Wise dataset.**

The internship was structured into **4 weeks**, each with a focus on 
a critical stage of the data science lifecycle:  
**Data Cleaning → Exploratory Data Analysis (EDA) → Predictive Modeling → Presentation & Reflection.**

----

## Project Overview

### Week 1: Data Cleaning & Feature Engineering
- **Tasks Completed:**
  - Standardized and cleaned raw dataset (handled missing values, removed duplicates, ensured consistent data types).
  - Created **new features**:
    - `Age` → learner age at time of application.
    - `Application_Lag_Days` → days between signup and application.
    - `Opportunity_Duration_Days` → length of program.
    - `Status_Group` → simplified version of status categories.
    - `Region` → grouped countries into regions.
- **Deliverables:**
  - [📑 Week 1 Report](Week1_Data_Cleaning/Week1_Report.pdf)  
  - [🗂 Cleaned Dataset](Week1_Data_Cleaning/Cleaned_Preprocessed_Dataset_Week1.csv)  
  - [📓 Notebook](Week1_Data_Cleaning/Week1_Notebook.ipynb)

---

### 🔹 Week 2: Exploratory Data Analysis (EDA)
- **Tasks Completed:**
  - Generated **descriptive statistics** (mean, median, mode, standard deviation).  
  - Identified correlations and outliers.  
  - Produced multiple **visualizations**:
    - Signup trends over time
    - Churn by region
    - Age distribution
    - Opportunity duration analysis
- **Key Insights:**
  - Shorter opportunities → higher churn  
  - Delays between signup & application strongly predict drop-offs  
  - Age and region have moderate influence  
- **Deliverables:**
  - [📑 Week 2 Report](Week2_EDA/Week2_EDA_Report.pdf)  
  - [📓 Notebook](Week2_EDA/Week2_Notebook.ipynb)  
  - [📊 Visuals](Week2_EDA/visuals/)

---

### 🔹 Week 3: Churn Analysis & Predictive Modeling
- **Tasks Completed:**
  - Defined **churn mapping** from `Status Description` and `Status Group`.  
  - Built predictive models:
    - Logistic Regression
    - Random Forest
  - Evaluated performance using **accuracy, precision, recall, and confusion matrix**.  
  - Analyzed **feature importance**.
- **Key Findings:**
  - **Opportunity Duration** was the strongest predictor (shorter = higher churn).  
  - **Internship opportunities** showed significantly higher churn rates.  
  - **Application Lag** and **Tenure** were top behavioral factors influencing churn.  
- **Deliverables:**
  - [📑 Week 3 Report](Week3_Churn_Modeling/Week3_Report.pdf)  
  - [📓 Notebook](Week3_Churn_Modeling/Week3_Notebook.ipynb)  
  - [📂 Model Outputs](Week3_Churn_Modeling/model_outputs/)  

---

### 🔹 Week 4: Final Presentation & Reflection
- **Tasks Completed:**
  - Consolidated Weeks 1–3 into a **PowerPoint presentation**.  
  - Developed **actionable recommendations** for student retention:  
    - Early engagement nudges (reduce signup → application lag).  
    - Structured mentorship for internships.  
    - Milestone-based program design.  
    - Seasonal campaigns during high-churn months.  
  - Created a **reflection video & document** summarizing personal growth.  
- **Deliverables:**
  - [📑 Final Presentation](Week4_Final_Presentation/Final_Presentation.pptx)  
  - [📑 Reflection Document](Week4_Final_Presentation/Internship_Reflection.pdf)

---

## 🛠 Tools & Libraries
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Jupyter Notebook**  
- **Excel & PowerPoint** for reports and presentation  
- **GitHub** for version control  

---

## 📊 Key Insights Across Weeks
- **Program Factors:** Shorter opportunities & internships → higher churn.  
- **Behavioral Factors:** Application lag increases churn; longer tenure reduces it.  
- **Demographics:** Younger learners slightly more churn-prone; region had minor effects.  
- **Timing:** Certain months showed higher churn, likely exam/holiday seasons.  

---

## 📌 Final Recommendations
1. Implement **early nudges** (emails, reminders) within 48 hours of signup.  
2. Provide **mentorship & structure** for internships to reduce churn.  
3. Design **longer programs or milestones** to increase commitment.  
4. Use **seasonal campaigns** during high-churn months.  
5. Focus on **behavioral data** rather than demographics for retention strategies.  

---

✨ This project demonstrates my skills in **data cleaning, exploratory analysis, predictive modeling, and insights communication** — all key components of the data science workflow.
