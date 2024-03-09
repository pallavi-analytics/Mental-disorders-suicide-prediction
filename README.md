# A Study on Global Mental Disorders and Suicide: Predictive Modeling

The escalation of mental health concerns, often leading to severe consequences like self-harm and suicide, underscores a critical global issue. This project aims to develop predictive models linking major mental disorders with suicide risk. Utilizing machine learning algorithms such as K-Nearest Neighbors, Random Forest, Gradient Boosting, XGBoost, and neural networks, the research conducts a comparative analysis to identify the most effective model for optimal performance.

# Dataset
The project utilizes datasets sourced from "Our World in Data," focusing on mental health issues. Several datasets are combined to create a curated dataset tailored for the analysis

# Data preparation and EDA
The research is focused on the different nations, so continents and other groupings are excluded. The final data set is checked for Null/missing values and preliminary
descriptive analysis is conducted for all relevant columns. To further explore the data: 

- Prevalence of the mental disorders across countries are analyzed
- Trends of the disorders over three decades (1990 - 2001) are observed.
- Gender-specific prevalence of mental disorders are visualized.
- The individual contribution of each mental disorder towards DALYs is realized.
- To visualize suicide rates on a global scale, the top 10 countries with the highest rates of suicides are presented.

# Statistical Analysis
Correlation analysis between variables and hypothesis testing (T-test and ANOVA) are conducted to establish associations or links between variables.

# Predictive Modelling
- K-Nearest Neighbors (KNN)
- Random Forest
- Gradient Boosting
- XGBoost
- Neural Network

Additionally, K-fold and repetitive K-folds are applied to ensure bias removal in the analysis.

# Result
All the five models are assessed in terms of two critical metrics : RMSE and R&sup2;
XGBoost stands out as the top-performing model,boasting the lowest RMSE and a near-perfect R&sup2; score.



 
 


