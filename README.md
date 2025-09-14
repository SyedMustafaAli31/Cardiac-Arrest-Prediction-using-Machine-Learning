# Cardiac-Arrest-Prediction-using-Machine-Learning
This project applies Machine Learning algorithms to predict the likelihood of cardiac arrest (heart disease) based on patient health attributes. It covers the complete pipeline from EDA to model evaluation.

📌 Project Workflow
Data Exploration & Visualization
Target distribution
Gender distribution (pie chart)
Correlation heatmap
Feature Selection
Used SelectKBest with ANOVA F-test to identify the top features.
Model Training & Comparison
Trained multiple ML algorithms and compared their performance:
Logistic Regression
Decision Tree
Random Forest
XGBoost
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Evaluation Metrics
Accuracy Score
Classification Report
Model Comparison

📊 Results
Each model was trained on scaled data, and their accuracies were compared. Random Forest and XGBoost showed strong performance, while Logistic Regression provided a reliable baseline.

🚀 Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost

🎯 Key Learnings
Importance of feature scaling in distance-based models like KNN and SVM.
How different algorithms perform on the same dataset.
Practical experience in building a real-world ML pipeline.
