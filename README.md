# Leveraging-Explainable-AI-to-Identify-Determinants-of-Lifetime-HIV-Testing-in-Tennessee-BRFSS-2023

Leveraging Explainable AI to Identify Determinants of Lifetime HIV Testing in Tennessee Adults: Evidence for Targeted Public Health Strategies from BRFSS 2023

Abstract

Background: HIV testing is a cornerstone of prevention and care, yet disparities in testing uptake persist across populations. 
Traditional statistical approaches may not fully capture the non-linear interactions among sociodemographic, behavioral, and health-related factors 
influencing HIV testing. This study used explainable AI in addition to traditional epidemiological methods to identify determinants of lifetime HIV testing 
among adults in Tennessee, United States.

Methods: This study applied both traditional and machine learning (ML) techniques to predict lifetime HIV testing among 4,911 (4,897,471 weighted) 
adults in Tennessee using the 2023 Behavioral Risk Factor Surveillance System (BRFSS) dataset. Sociodemographic, behavioral, and health-related characteristics 
were examined. A set of machine learning algorithms were trained using an 80/20 stratified train–test split, with 5-fold stratified cross-validation applied 
within the training data. Model performance was evaluated on the unresampled test set using relevant metrics. SHAP and LIME were used for model interpretability.

Results: The weighted prevalence of lifetime HIV testing was 38.8% among adults in Tennessee. Across ML models, Extreme Gradient Boosting (XGBoost) demonstrated 
the strongest overall discriminatory performance achieving the highest AUROC (0.718), PR-AUC (0.583), competitive performance across accuracy (0.694), 
precision (0.595), recall (0.447), and F1-score (0.511). The most influential predictors include age group, smoking status, veteran status, race/ethnicity, 
mental health status, marital status, income group, education level, physical health status, and sex.

Conclusion: Machine learning, particularly XGBoost, provides a robust and interpretable framework for predicting HIV testing behaviors in population-based survey data. 
Integrating ML with explainable AI methods can improve surveillance, support targeted interventions, and inform data-driven public health strategies.

Keywords: HIV testing, machine learning, SHAP analysis, LIME analysis, behavioral risk factor surveillance system, Tennessee
