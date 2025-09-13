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
Top Job Title: Machine Learning Researcher
Top Employment Type: FT (Full-Time)
Top Company Size: S (Small)
Top Experience Level: ML (Mid-Level)
Top Salary Currency: USD
Top Education Required: Bachelor
Top Industry: Retail
Top Employee Residence: Sweden

## Salary Insights
Highest Salary: Machine Learning Engineer
Lowest Salary: AI Consultant
Industries with Highest Salaries: Media, Retail
Top Company by Highest Salaries: TechCorp Inc
Lowest Salary Company: Algorithmic Solutions

## Remote & Benefits Insights
Remote Ratio: Nearly same across jobs, highest for Computer Vision roles
Job with Biggest Benefits Score: Machine Learning Research
Top Companies by Benefits: TechCorp Inc, Cognitive Computing

## Skill & Education Insights
Most Frequent Skills: Top skills identified per job title
Education Level Requirement: Most roles require Bachelor’s degree

## Numerical & Outlier Analysis
Salary Outliers: Identified and clipped using IQR method
Average, Max, Min Salaries: Computed per company size and employment type

## Visualizations Performed
Salary distribution
Average salary by experience level
Remote ratio distribution
Job count by employment type
Salary by company size
Salary distribution by company location
Top 20 skills required
Education level requirement
Job postings over time
Correlation heatmap


