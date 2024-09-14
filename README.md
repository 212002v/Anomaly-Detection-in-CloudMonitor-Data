# Anomaly-Detection-in-CloudMonitor-Data
CloudMonitor Anomaly Detection with RandomForest & SHAP
Project Overview
This project aims to detect anomalies in cloud infrastructure monitoring data, such as CPU utilization metrics. By leveraging a RandomForest Classifier and SHAP (SHapley Additive exPlanations), the project provides both anomaly detection and interpretability for the model's decisions.

Key Objectives
Anomaly Detection: Automatically identify abnormal patterns in cloud infrastructure monitoring metrics.
Explainability: Utilize SHAP to provide insights into the model's predictions, highlighting influential features.
Visualization: Offer time series visualizations of data, showcasing normal and anomalous behavior.
Project Features
Data Preprocessing: Handle missing or noisy values in cloud metric datasets and prepare data for model training.
Anomaly Detection: Train a RandomForest model to classify data points as normal or anomalous based on cloud monitoring metrics.
Model Explainability: Employ SHAP to explain the contribution of each feature in determining anomaly status.
Data Visualization: Visualize time series data alongside detected anomalies for enhanced understanding of the model's outputs.
Dataset
The dataset used in this project contains cloud infrastructure monitoring data. Each dataset includes:

value: The observed metric (e.g., CPU utilization).
anomaly: A flag indicating if the data point is normal (1) or an anomaly (-1).
Example: ec2_cpu_utilization_5f5533.csv

Workflow
Data Preprocessing: Load and preprocess cloud monitoring data, addressing missing values and noise.
Model Training: Train a RandomForest Classifier using preprocessed data.
Explainability with SHAP: Apply SHAP to interpret model predictions and identify key features.
Anomaly Visualization: Visualize time series data with anomaly annotations.
Visualization
Time series plots highlighting anomalies in cloud monitoring metrics.
SHAP summary plots showcasing feature contributions for anomaly classification.

Run the Project:
Bash
python main.py
Use code with caution.
