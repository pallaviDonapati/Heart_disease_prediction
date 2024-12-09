# Heart_disease_prediction
This project aims to predict heart disease by analyzing patient health metrics using machine learning and deep learning techniques. It provides a streamlined approach to detect the likelihood of heart disease through multiple algorithms and tools.

Project Overview
The repository showcases the implementation of several machine learning models to classify heart disease. The process involves detailed exploratory data analysis (EDA), preprocessing steps, and model performance evaluation.

Repository Contents
Heart_Disease_Prediction.ipynb: Jupyter notebook containing EDA, model training, and evaluation code.
heart.csv: Dataset used for training and testing models.
requirements.txt: List of dependencies for replicating the project.
Model Training Steps
Data Preparation:

Loaded and cleaned the dataset, handled missing values, and performed feature scaling.
Explored feature importance through correlation heatmaps and pair plots.
Model Selection:

Trained multiple models, including Logistic Regression, Naive Bayes, Decision Tree, Random Forest, SVM, and XGBoost.
Neural Network developed using Keras to explore deep learning applications.
Hyperparameter Tuning:

GridSearchCV optimized model parameters for SVM and Random Forest, achieving maximum performance.
Model Evaluation:

Accuracy, precision, recall, and F1 scores were calculated for each model.
Random Forest achieved the highest accuracy of 90.16% after tuning.
App Features (Optional Integration):
A Streamlit-based app can be developed for user-friendly interaction.
Users can input patient data and receive predictions in real-time.
Tools and Technologies
Python, pandas, scikit-learn, XGBoost, seaborn, TensorFlow.
