## COVID-19-Risk-Prediction Using Machine Learning

This project implements a machine learning model to predict the likelihood of COVID-19 infection based on a combination of diabetes-related metrics and COVID-19 symptoms. The model processes healthcare data to classify patients as "More Likely" or "Less Likely" to require medical attention, providing critical insights that can assist healthcare professionals in making timely decisions.

## Project Overview

The goal of this project is to predict the likelihood of severe COVID-19 complications based on a combination of health metrics (e.g., glucose levels, BMI, and age) and reported symptoms (e.g., fever, breathing problems, and cough). Using a Support Vector Classifier (SVC), the model analyzes these features to determine if a patient is at higher risk of severe infection, requiring immediate medical attention.

## Key Features:

   •	Data Integration: The project merges diabetes and COVID-19 datasets to create a comprehensive dataset for training and prediction.
    
   •	Predictive Modeling: Utilizes a Support Vector Machine (SVM) with a linear kernel to predict patient outcomes based on health features.
    
  •	Real-Time Prediction Interface: Built an interactive user interface using Gradio to allow real-time COVID-19 risk assessment based on user input.

## Business Application:

   •	Healthcare: Provides a tool to predict patients' likelihood of severe COVID-19 infection based on their pre-existing conditions and symptoms. This can be used for triaging patients and prioritizing care.

   •	Preventive Measures: Helps healthcare organizations identify at-risk patients early, reducing the strain on healthcare systems and improving patient outcomes.

## Tools & Technologies Used:

   •	Programming Languages: Python
    
   •	Libraries:
    
     •	pandas and numpy for data manipulation
      
     •	matplotlib for visualization
      
     •	scikit-learn for machine learning (SVM)
      
     •	Gradio for building the real-time interactive interface
    
   •	Modeling:
      
     •	Supervised learning using Support Vector Classifier (SVC) with a linear kernel
      
     •	Evaluation of model accuracy using scikit-learn metrics module

## Project Workflow:

1.	Data Preprocessing:

    •	Combined two datasets (diabetes-related data and COVID-19 symptoms) and cleaned them by removing missing values.
    
    •	Dropped unnecessary columns and ensured that the dataset was ready for model training.

2.	Model Training:

    •	Used a Support Vector Classifier (SVC) to classify patients based on their risk of COVID-19 complications.
    
    •	The model was trained using the combined dataset, splitting into training and test sets for validation.
    
    •	Achieved an accuracy of 94% on the test dataset.

3.	Prediction Logic:

    •	Based on health metrics like Glucose (>=140 mg/dL), Age (>=50), and symptom presence (e.g., fever, breathing problems), the model determines if a patient is "More Likely" or "Less Likely" to require medical attention.

4.	Real-Time Interface:

    •	Deployed an interactive interface using Gradio where users can input their health data and symptoms to receive real-time predictions on their COVID-19 risk status.
