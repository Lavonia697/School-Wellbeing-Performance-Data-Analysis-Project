# School-Wellbeing-Performance-Data-Analysis-Project

An end-to-end Python data analytics project exploring factors influencing learner performance and wellbeing.

---

## Project Overview
This project analyzes school performance using real-world educational and wellbeing indicators to understand how non-academic factors influencing learner outcomes.

*Key indicators include:*
- Attendance rate
- Math score performance
- Household income
- Mental health indicators
- Extracurricular participation
- Parental involvement

The goal is to support NGOs, schools, and education-focused organizations with data-driven insights that inform early interventions and policy decisions.

---

## Analysis Workflow
1. Data ingestion and inspection
2. Data cleaning and preprocessing in Python
3. Feature engineering and risk flag creation
4. Exploratory data analysis (EDA)
5. Visualization of key wellbeing-performance relationships
6. Insights generation and recommendations

---

1. ## Data Cleaning & Feature Engineering
   ### Key steps performed in Python:
   - Removal of duplicate records
   - Handling missing values using median and mode strategies
   - Standardization of column names and data types
   - Feature engineering:
       - *Performance_Level*- categorized learners into low, medium, and high              performance
      -  *Socioeconomic_Index* - composite indicator derived from household                 income variables
     -  *Concern_Flag* - flags learners at risk based on attendance, income, and            mental health

  ---
## Documentation
A detailed explanation of the analytical approach and data preparation steps is available in the [Documentation](Documentation/methodology.md).

---

 2. ## Key Visualizations
*The following visual analyses were created using Matplotlib and Seaborn:*
  1. ### Attendance vs Math Score
     Demonstrates the positive relationship between consistent attendance and           academic performance.
     
  2. ### Correlation Heatmap
     Highlights variables with the strongest association to math scores.

  3. ### Income vs Mental Health Score
     Shows how socioeconomic conditions impact learner wellbeing.

  4. ### Math Score vs Parental Involvement
     Illustrates the influence of family engagement on academic outcomes.

  5. ### Mental Health vs Extracurricular Participation
     Explores how participation in extracurricular activities to mental wellbeing.

  ---

  3. ## Key Insights
  - Attendance is a strong predictor of academic performance, with learners above     85% attendance achieving higher average math scores.
  - Household income significantly influences mental health, with lower-income
  - learners reporting higher stress levels.
  - Mental wellbeing directly affects academic outcomes, reinforcing the need for     holistic learner support.
  - A high-risk learner group was identified based on:
      - Low attendance
      - Low household income
      - Poor mental health
      - Low academic performance
  * This group should be prioritized for targeted interventions.*
 
  ---

## Project Documentation

 **Analysis Notebook**  
- [School Wellbeing Performance_Data Analysis_Project (Jupyter Notebook)](notebooks/School_Wellbeing_Performance_Project_Portfolio.ipynb)

 **Methodology Document**  
- [Data Cleaning & Analytical Methodology](Documentation/methodology.md)




  ---

  ## Tools Used
  - Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Jupyter Notebook
 
---

## Project Impact
*This analysis helps education-focused organizations:*
- Identify at-risk learners early
- Allocate resources more effectively
- Design targeted wellbeing interventions
- Advocate for data-backed education policies

---

## Author
Data Entry Specialist | Junior Data Analyst



  
     














