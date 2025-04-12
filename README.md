# Description
This repository analyzes factors influencing the length of hospital stay among patients receiving carbapenem therapy for multidrug-resistant infections in northern Peninsular Malaysia. The study employs a multilevel linear mixed model to account for variations at the hospital level.

Additionally, it includes a training section on using a multilevel logistic regression model to investigate factors predicting post-myocardial infarction (MI) mortality across multiple hospitals.

# Dataset
The repository contains two simulated datasets:

- Carbapenem Therapy Dataset: Includes patient demographics, clinical factors (e.g., SOFA score, therapy type), and hospital stay duration.
- MI Mortality Dataset: Contains data on 1,250 patients from 7 hospitals, focusing on factors predicting mortality following myocardial infarction.

# Methodology
- Exploratory Data Analysis (EDA)
- Single & Multiple Linear Regression
- Multilevel Analysis with random intercept and slope models
- Tabulation and visualization

# Reproducibility
Code is written in R using lme4, broom.mixed, gtsummary and other relevant packages.

The analysis can be reproduced by running the following files:

- linear mixed model.qmd for the carbapenem therapy analysis.
- logistic mixed model.qmd for the MI mortality analysis.

# Contact
For any inquiries, please contact drhazlienor@hotmail.com.
