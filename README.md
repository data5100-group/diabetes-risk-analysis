# Diabetes-risk-analysis
Diabetes is a major chronic condition affecting hundreds of millions globally and driving substantial healthcare burden. Early identification of individuals at high risk for diabetes and effective management of diagnosed patients are critical for preventing complications and reducing healthcare utilization. This project focuses on two interconnected but distinct predictive problems: identifying clinical and demographic predictors of diabetes in the general population and identifying predictors of 30-day hospital readmission among patients already diagnosed with diabetes. These goals reflect both prevention and disease-management priorities in public health.


Project Overview
Objective:
The first objective leverages a large, diverse Kaggle clinical dataset to determine which measurable factors most strongly distinguish individuals with diabetes from those without. The second objective draws on the U.S. hospital readmission dataset from the UCI Machine Learning Repository to assess whether commonly recorded care-utilization variables can reliably predict early rehospitalization-an important but difficult-to-manage quality metric.
Together, these analyses help clarify what drives diabetes onset versus challenges in ongoing diabetes management.

Domain: Health 
Key Techniques: The methodologies used were data cleaning, handling missing values, exploratory data analysis, correlation analysis, logistic regression, random forest, non-linear regression alongside OLS results to interpret results.
Project Structure
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
Data
Source: https://github.com/data5100-group/diabetes-risk-analysis

Strack B, DeShazo JP, Gennings C, Olmo J L, Ventura S, Cios K J, Clore J. 2014. Impact of HbA1c measurement on hospital readmission rates: analysis of 70,000 clinical database patient records. BioMed Research International, 2014. VCU Scholars Compass+1

Diabetes 130-US Hospitals for Years 1999-2008. UCI Machine Learning Repository (2014). UCI Machine Learning Repository+1

100,000 Diabetes Clinical Dataset. Kaggle (Choksi, 2023). Baselight+1

Zarghani A. et al. 2024. Comparative Analysis of LSTM Neural Networks and Traditional Machine Learning Models for Predicting Diabetes Patient Readmission. arXiv. arXiv

Sarthak, Shukla & Tripathi (2020). EmbPred30: Assessing 30-days Readmission for Diabetic Patients using Categorical Embeddings. arXiv. arXiv

Hasan M., Yasmin F. 2025. Predicting Diabetes Using Machine Learning: A Comparative Study of Classifiers. arXiv.

Description: Hospital readmission among diabetic patients is a major concern: repeated admissions contribute substantially to healthcare costs, morbidity, and complications. Prior work has shown that poor glycemic control, insufficient monitoring, and inadequate transitions of care contribute to readmission risk. For example, the original study introducing the 130-US Hospitals dataset found that measurement of HbA1c during hospitalization was infrequent (~ 18.4%) and that readmission risk varied significantly depending on whether HbA1c was measured.
On the other hand, early detection of undiagnosed diabetes (or pre-diabetes) in outpatient or general clinical populations is critical for initiating lifestyle or medical interventions before complications arise. Large-scale efforts to predict diabetes based on clinical risk factors can inform public health screening strategies and individual risk profiling.
Advances in machine learning over the past decade — including non-linear models, regularization, feature engineering, and ensemble methods — have made it feasible to develop predictive models with reasonable accuracy and interpretability. These models can help identify high-risk patients automatically, potentially guiding clinical decisions or resource allocation. Indeed, recent work has demonstrated success in readmission prediction using both traditional ML and deep-learning methods on the 130-US dataset.

License: (if applicable)

Analysis

The ROC curve analyses show how well each model separates positive from negative cases. For diabetes prediction, the logistic regression and random forest models both achieve strong discrimination, with AUC values near 1.0, while the hospital readmission logistic regression model performs only modestly (AUC ≈ 0.63), indicating limited predictive strength.

Feature importance results from the diabetes random forest model show that glucose-related biomarkers (HbA1c and blood glucose) are the strongest predictors, followed by age, BMI, and cardiometabolic conditions. Demographic factors contribute very little once clinical variables are included. For the hospital readmission model, the number of medications is the strongest predictor, followed by length of stay, inpatient visits, and number of diagnoses, reflecting that complex and chronic medical needs drive readmission risk.

Comparisons highlight that ROC curves assess *overall model performance*, while feature importance charts identify *which variables influence predictions*. Strong performance does not necessarily depend on many features, and weak performance can still reveal meaningful clinical drivers.

The non-linear regression analyses show that glucose levels and hospital stay duration can be better understood using squared terms, revealing curved, non-linear relationships. However, these models explain only modest portions of variability (6% for glucose, 23% for hospital stay), and multicollinearity is present due to the inclusion of squared variables. Overall, the regression results show that clinical factors matter but do not capture the full complexity of patient outcomes.


Results
Across the two clinical datasets, predictive performance differed substantially depending on the outcome of interest. In the diabetes dataset, both logistic regression and random forest models achieved very strong discrimination, with AUC values close to 0.96, indicating reliable identification of diabetes status using clinical variables such as HbA1c, blood glucose, BMI, age, hypertension, and heart disease. In contrast, hospital readmission models trained on the UCI dataset showed only modest predictive ability. The logistic regression ROC curve produced an AUC of approximately 0.63, demonstrating limited accuracy in identifying patients who would be readmitted within 30 days. Feature importance from the random forest model showed that medication counts, length of stay, prior inpatient encounters, and number of diagnoses were most influential, but despite these associations, predictive performance remained weak. Non-linear OLS models additionally showed meaningful relationships between clinical variables and both blood glucose levels and time in hospital, including significant curved effects from polynomial terms, although the overall variance explained was relatively small. Taken together, these results suggest that diabetes onset is highly predictable using common clinical measures, whereas short-term readmission is considerably more difficult to model using standard administrative variables alone.

Authors
Your Name - Gurpreet Kaur, Badamgarav Battushig, Naomi Le Mouel
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Jupyter Notebook
Google Colab
Microsoft Word
Adobe Acrobat
Github Repository
