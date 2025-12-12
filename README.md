# DIABETES RISK ANALYSIS
# A Comparative Analysis of Clinical Predictors for Diabetes and Hospital Readmission

## Introduction
Diabetes is a major chronic condition affecting hundreds of millions globally and driving substantial healthcare burden. Early identification of individuals at high risk for diabetes and effective management of diagnosed patients are critical for preventing complications and reducing healthcare utilization. This project focuses on two interconnected but distinct predictive problems: identifying clinical and demographic predictors of diabetes in the general population and identifying predictors of 30-day hospital readmission among patients already diagnosed with diabetes. These goals reflect both prevention and disease-management priorities in public health.
The first objective leverages a large, diverse Kaggle clinical dataset to determine which measurable factors most strongly distinguish individuals with diabetes from those without. The second objective draws on the U.S. hospital readmission dataset from the UCI Machine Learning Repository to assess whether commonly recorded care-utilization variables can reliably predict early rehospitalization-an important but difficult-to-manage quality metric.
Together, these analyses help clarify what drives diabetes onset versus challenges in ongoing diabetes management.

## Project Overview
This project examines diabetes diagnosis and hospital readmission risk using publicly available clinical datasets. The analysis focuses on identifying key clinical and demographic factors associated with diabetes and understanding patterns of 30-day hospital readmissions among diabetic patients. By comparing predictors across datasets, the project highlights common risk factors that influence both diabetes outcomes and readmission likelihood, offering insight into broader challenges in diabetes management and care.


---

## Project Participants
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
   - Summarize and visualize demographic and clinical variable distributions.  
   - Examine relationships between key variables such as glucose, BMI, and age.  
   - Identify missing values, inconsistencies, and potential outliers.

2. **Statistical and Predictive Modeling**  
   - Perform hypothesis testing to compare diabetic and non-diabetic patient groups.  
   - Build predictive models to estimate diabetes and readmission risk.  
   - Compare feature importance across datasets to identify consistent predictors.

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
- Code Sharing and Version Control: GitHub repository  
- Meeting Schedule: Weekly check-in every Wednesday at 9:00 AM PST  
- Shared Notes and Drafts: Google Docs  
- Presentation Collaboration: Google Slides  

## Results

Our analysis showed that laboratory measures related to glycemic control were the strongest predictors of diabetes and hospital readmission risk. Across all models, HbA1c and blood glucose consistently contributed the most to predictive performance, confirming their clinical relevance. Body mass index and age also had meaningful influence, reflecting known metabolic and demographic risk factors. Comorbid conditions such as hypertension and heart disease provided additional, though smaller, improvements in prediction accuracy. In contrast, most demographic variables had relatively low importance once clinical indicators were included, suggesting that medical and physiological features play a larger role in identifying diabetes-related outcomes than demographic characteristics alone.

## Authors

- Gurpreet Kaur
- Badamgarav Battushig
- Naomi Le Mouel

---

## References

- Strack, B., DeShazo, J. P., Gennings, C., Olmo, J. L., Ventura, S., Cios, K. J., & Clore, J. (2014).  
  *Impact of HbA1c measurement on hospital readmission rates: Analysis of 70,000 clinical database patient records.*  
  BioMed Research International, 2014.

- UCI Machine Learning Repository. (2014).  
  *Diabetes 130-US hospitals for years 1999–2008.*  
  https://archive.ics.uci.edu/

- Choksi, S. (2023).  
  *100,000 diabetes clinical dataset.*  
  Kaggle. https://www.kaggle.com/

- Zarghani, A., et al. (2024).  
  *Comparative analysis of LSTM neural networks and traditional machine learning models for predicting diabetes patient readmission.*  
  arXiv.

- Sarthak, Shukla, & Tripathi. (2020).  
  *EmbPred30: Assessing 30-days readmission for diabetic patients using categorical embeddings.*  
  arXiv.

- Hasan, M., & Yasmin, F. (2025).  
  *Predicting diabetes using machine learning: A comparative study of classifiers.*  
  arXiv.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Google Colab  
- Google Slides  
- Microsoft Word  
- Adobe Acrobat  
- GitHub
- Capcut
- Canvas
- Microsoft Teams

---


