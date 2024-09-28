# Project Overview
This project is focused on predicting the safety of different locations for women using machine learning. The model uses factors like area, time, and surroundings 
(e.g., police stations or bars) to predict if a location might be safe or unsafe.

# Features
Safety Prediction: The model predicts if an area is safe or risky.
Balanced Dataset: Uses SMOTE to handle imbalanced data (more risky cases vs safe cases).
Logistic Regression: A machine learning algorithm (Logistic Regression) is used to make predictions.
Real-Time Prediction: You can input new location data and get instant safety predictions.

# Technologies Used
Python: Main programming language.
Libraries:
Pandas: For handling data.
NumPy: For performing calculations.
Scikit-learn: For building and evaluating machine learning models.
Imbalanced-learn (SMOTE): This is used to balance the dataset.
Matplotlib & Seaborn: For data visualization.

# How It Works
Load Data: Reads the dataset containing location details and safety records.
Preprocess Data: Encodes categorical data (like area, and time) and applies feature scaling.
Handle Imbalance: Uses SMOTE to balance the dataset by generating new samples for the minority class.
Train the Model: Logistic regression is used to train the model with the balanced data.
Evaluate Model: Measures accuracy, cross-validation score, ROC-AUC, and generates a confusion matrix to see how well the model performs.
Make Predictions: You can input new location data, and the model will predict if the location is safe or not.

# Usage
Train the Model: The model will be trained on the dataset, and after training, it can predict the safety of new locations.
Predict Safety: Enter new location details (e.g., area, time, people frequency) and get a prediction on whether the location is safe or not.

# Future Improvements
Better Model: Try using different algorithms to improve prediction accuracy.
Mobile App: Build a mobile app so users can easily access the predictions.
Real-Time Data: Integrate real-time location and safety data for more accurate predictions.

# Contributing
Feel free to submit issues or make pull requests if you would like to contribute to improving this project.
