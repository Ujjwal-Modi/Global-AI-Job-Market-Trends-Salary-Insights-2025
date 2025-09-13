# Global-AI-Job-Market-Trends-Salary-Insights-2025
This project involves a comprehensive workflow for analyzing a dataset of machine learning job postings. The process begins with data preprocessing and cleaning, including handling missing values, encoding categorical variables, and clipping outliers. Feature engineering is performed to create meaningful variables and select relevant features for modeling. 

Exploratory data analysis (EDA) is conducted to visualize distributions, correlations, and relationships between features such as salary, experience, remote ratio, company size, and benefits. Both classification and regression models are built depending on the target variable, using a variety of algorithms including linear models, ensemble methods, and gradient boosting techniques. Hyperparameter tuning is applied to advanced models like LightGBM and CatBoost using Bayesian optimization.

Model performance is evaluated with appropriate metrics, and visualizations such as scatter plots, residual plots, and feature importance charts are generated to interpret and communicate the results effectively.

# Binary Classification
This file contains a complete binary classification workflow on the machine learning jobs dataset. It includes data preprocessing, feature engineering, and encoding of categorical variables. Multiple classification models were trained, including Logistic Regression, Random Forest, Decision Tree, SVM, Naive Bayes, KNN, Gradient Boosting, AdaBoost, ExtraTrees, XGBoost, LightGBM, CatBoost, and linear models such as Perceptron, RidgeClassifier, and SGDClassifier. Models were evaluated using accuracy, precision, recall, F1-score, and visualized with confusion matrices, ROC-AUC curves, precision-recall curves, feature importance plots, and SHAP values for interpretability. The best-performing model (LightGBM) was further optimized using Bayesian Search (BayesSearchCV) for hyperparameter tuning. All code, analysis, and visualizations are combined in this single file to provide a comprehensive overview of the binary classification workflow.

# Regression
This file contains a comprehensive regression analysis of the machine learning jobs dataset. After preprocessing and feature engineering, multiple regression models were trained and compared using metrics such as MSE, RMSE, MAE, and R². The best-performing model, LightGBM Regressor, was further optimized using Bayesian Search (BayesSearchCV) for hyperparameter tuning. Model performance was visualized through actual vs. predicted plots and residual plots to assess accuracy and model fit. All code, analysis, and visualizations are included in this single file to provide a complete workflow for regression modeling.

# EDA_&_Visualization
This file contains a comprehensive data analysis and visualization workflow for the machine learning jobs dataset. It includes exploratory data analysis (EDA) of features such as salary, job title, experience level, employment type, company size, education, remote ratio, industry, and employee location. Various visualizations such as distributions, correlation heatmaps, and feature importance charts are included to explore patterns, trends, and relationships between features. All analysis and visualizations are combined in this single file to provide a complete overview of the dataset.

## Dataset Insights & Visualizations
The dataset was analyzed to extract key insights. The most common job title is Machine Learning Researcher, with full-time (FT) employment being the most frequent type. Most companies are small (S), and the majority of employees are at a mid-level experience (ML). The predominant salary currency is USD, and most roles require a Bachelor’s degree. The retail industry is the most common, and Sweden emerges as the top employee residence location.

## Salary Insights
Salary analysis revealed that Machine Learning Engineers earn the highest salaries, while AI Consultants earn the lowest. Media and Retail industries offer the highest compensation, with TechCorp Inc identified as the company offering the top salaries. The lowest-paying company in the dataset is Algorithmic Solutions.

## Remote & Benefits Insights
The remote ratio is generally consistent across jobs, with Computer Vision roles having the highest flexibility. Machine Learning Research positions have the highest benefit scores, and the top companies providing benefits are TechCorp Inc and Cognitive Computing.

## Skill & Education Insights
Skill analysis highlights the most frequent skills required per job title. Additionally, the majority of roles require a Bachelor’s degree, confirming the educational expectations for the positions.

## Numerical & Outlier Analysis
Outliers in salaries were identified and clipped using the IQR method to maintain data consistency. Average, maximum, and minimum salaries were computed for each company size and employment type to understand compensation trends.

## Visualizations Performed
The dataset was visualized through various charts including salary distribution, average salary by experience level, remote ratio distribution, job count by employment type, salary by company size, salary distribution by company location, top 20 skills required, education level requirements, job postings over time, and a correlation heatmap. These visualizations provide a clear and comprehensive overview of the dataset.


