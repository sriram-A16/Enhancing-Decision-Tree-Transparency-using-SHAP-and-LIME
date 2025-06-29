***Drug Classification Using Decision Tree Classifier***

This project explores the classification of drugs using a Decision Tree classifier, leveraging patient data such as age, gender, blood pressure, cholesterol levels, and the sodium-to-potassium ratio. The model aims to provide interpretable predictions to enhance personalized medicine.

**Table of Contents**

Project Overview
Dataset
Installation
Usage
Model Evaluation
Interpretability
Results
Project Overview

This research utilizes a Decision Tree classifier to predict drug prescriptions based on various patient characteristics. The model is trained using a 70/30 train-test split and evaluated using metrics such as precision, recall, F1-score, and confusion matrix. Cross-validation ensures the model's generalization capability.

**Dataset**

The dataset used in this project is drug200.csv, which contains the following features:

Age: Age of the patient
Sex: Gender of the patient
BP: Blood pressure level (e.g., HIGH, NORMAL, LOW)
Cholesterol: Cholesterol level (e.g., NORMAL, HIGH)
Na_to_K: Sodium-to-potassium ratio
Drug: The prescribed drug class

Link:
https://www.kaggle.com/datasets/pablomgomez21/drugs-a-b-c-x-y-for-decision-trees

**Installation**

pip install shap lime pandas scikit-learn matplotlib seaborn

**Model Evaluation**

The model is evaluated through:

Confusion Matrix: Visual representation of true vs. predicted classifications.
Classification Report: Metrics including precision, recall, and F1-score.
Cross-Validation: Ensures the robustness of the model.
Interpretability

To foster transparency and interpretability, SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) are employed for:

Global Insights: Understanding the overall feature contributions to the model.
Local Insights: Analyzing individual predictions.
Additionally, Partial Dependence Plots (PDPs) and decision tree diagrams clarify interactions between patient characteristics and drug outcomes.

**Results**

The integration of machine learning with interpretability methods demonstrates the potential of AI to enhance personalized medicine, offering reliable, accurate, and transparent drug recommendations.

**Authors**

Alasakani Sriram  - B.Tech Student in Computer Science Engineering, VIT AP College. 

Pakanati Dwijesh  - B.Tech Student in Computer Science Engineering, VIT AP College.

Sai Kiran Kanuri  - B.Tech Student in Computer Science Engineering, VIT AP College.

Pulakam Tej Kiran - B.Tech Student in Computer Science Engineering, VIT AP College.

Akanksh Inampudi  - B.Tech Student in Computer Science Engineering, VIT AP College.
