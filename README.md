# Student-Success-Predictor-ML
This project predicts the key factors that affect student grades using machine learning models.

We use a dataset containing student information across various nationalities and grade levels, along with several influencing factors such as:

Number of hands raised in class

Number of attendance days

Number of hours studied

And more...

The goal is to identify and predict which features most significantly impact student performance.

Project Highlights:
Data Preprocessing:

Handling missing values

Balancing the dataset using SMOTE (Synthetic Minority Over-sampling Technique)

Model Building:

Multiple classifiers have been used and compared, including Logistic Regression, Decision Trees, Random Forest, SVM, and others.

Hyperparameter tuning performed using GridSearchCV for optimizing model performance.

Evaluation Metrics:

Accuracy

Confusion Matrix

Precision, Recall, F1-Score

Visualizations:

Feature importance graphs

Confusion matrices

Performance comparison charts

User Interface (GUI):

A simple and interactive GUI built using Tkinter or Streamlit that allows users to input student data and receive predictions instantly.

Technologies Used:
Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn (for SMOTE)

Matplotlib, Seaborn (for visualizations)

Tkinter / Streamlit (for GUI)

How to Run:
Clone the repository.

Install the required libraries from requirements.txt.

Run the preprocessing and training scripts to generate the models.

Launch the GUI to make predictions with new data!

Future Enhancements:
Deployment of the model as a web application.

Addition of more advanced ensemble models like XGBoost or LightGBM.

Real-time updating of models with new student data.

