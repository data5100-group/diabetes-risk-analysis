# DIABETES RISK ANALYSIS
# Comparative Analysis of Diabetes Risk Factors and Hospital Readmission Patterns

## Introduction
Diabetes is a major chronic condition affecting hundreds of millions globally and driving substantial healthcare burden. Early identification of individuals at high risk for diabetes and effective management of diagnosed patients are critical for preventing complications and reducing healthcare utilization. This project focuses on two interconnected but distinct predictive problems: identifying clinical and demographic predictors of diabetes in the general population and identifying predictors of 30-day hospital readmission among patients already diagnosed with diabetes. These goals reflect both prevention and disease-management priorities in public health.
The first objective leverages a large, diverse Kaggle clinical dataset to determine which measurable factors most strongly distinguish individuals with diabetes from those without. The second objective draws on the U.S. hospital readmission dataset from the UCI Machine Learning Repository to assess whether commonly recorded care-utilization variables can reliably predict early rehospitalization-an important but difficult-to-manage quality metric.
Together, these analyses help clarify what drives diabetes onset versus challenges in ongoing diabetes management.

## Project Overview
This project analyzes and compares two main aspects of diabetes care using publicly available healthcare datasets:
1. Identify key clinical and demographic factors associated with diabetes diagnosis.
2. Understand hospital readmission patterns among diabetic patients within 30 days.

The purpose is to discover common risk factors influencing both diabetes diagnosis and hospital readmissions, which may indicate systemic challenges in diabetes management.

---

## Team Members
- Gurpreet Kaur – gkaur6@seattleu.edu  
- Badamgarav Battushig – bbattushig@seattleu.edu  
- Naomi Le Mouel – nlemouel@seattleu.edu  

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data Sources
1. **Diabetes 130-US Hospitals (1999–2008)**  
   Source: UCI Machine Learning Repository  
   Link: https://archive.ics.uci.edu/dataset/296/diabetes-130-us-hospitals-for-years-1999-2008  

2. **100,000 Diabetes Clinical Dataset**  
   Source: Kaggle  
   Link: https://www.kaggle.com/datasets/priyamchoksi/100000-diabetes-clinical-dataset  

Both datasets contain sufficient information for demographic, clinical, and readmission-related analysis. Data preprocessing and cleaning will be required before performing analysis.

---

## Analytical Approach
1. **Exploratory Data Analysis (EDA)**  
   - Summarize and visualize demographic and clinical distributions.  
   - Examine correlations between variables such as glucose, BMI, and age.  
   - Identify missing values and outliers.

2. **Statistical and Predictive Modeling**  
   - Conduct hypothesis testing to compare diabetic vs. non-diabetic patients.  
   - Build predictive models to estimate readmission likelihood.  
   - Compare key features between datasets to identify shared predictors.

---

## Tools and Technologies
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook or Google Colab
- GitHub for collaboration and version control
- Microsoft PowerPoint and Word for presentation and reporting

---

## Project Challenges
- Merging two datasets with different schemas and formats.  
- Managing class imbalance in readmission data.  
- Ensuring the findings are statistically valid and clinically interpretable.

---

## Collaboration and Workflow
- Communication: Microsoft Teams  
- Code Sharing: GitHub repository  
- Meeting Schedule: Weekly check-in every Wednesday at 9 AM PST  
- Shared Notes: Google Docs

## Results

This analysis demonstrates a modest negative correlation between student–teacher ratios and ACT performance at the state level. While smaller class sizes appear to offer benefits, effective educational improvement requires multifaceted policy approaches. The student-teacher ratio is not a strong predictor to analyse the ACT scores.From the comparative analysis of the five socioeconomic variables, economic disadvantage (percent lunch) emerged as the most consistent and influential predictor of student performance.

## Authors

- Gurpreet Kaur
- Badamgarav Battushig
- Naomi Le Mouel

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Jupyter Notebook 
- Google Colab
- Microsoft Word
- Adobe Acrobat
- Github Repository

---


