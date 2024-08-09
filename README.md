# Wine Quality Prediction

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Introduction

This project focuses on predicting the quality of wine based on its physicochemical properties using a machine learning model. The model is developed and optimized in Databricks, enabling high accuracy predictions that can be deployed for real-time use.

## Project Overview

### Background

Wine quality is influenced by various chemical properties such as acidity, sugar levels, and alcohol content. Predicting wine quality based on these properties can assist winemakers in ensuring consistency and maintaining high standards. This project leverages machine learning to automate the prediction process, improving efficiency and decision-making in the wine industry.

### Objective

The main objective of this project is to build a robust machine learning model that can accurately predict wine quality based on physicochemical properties and deploy it for real-time predictions using Databricks.

## Features

- **Machine Learning Model:**
  - Developed using XGBoost to predict wine quality with high accuracy.
  - Experiment tracking and hyperparameter logging in Databricks to ensure model reproducibility and version control.

- **Hyperparameter Optimization:**
  - Employed Hyperopt to optimize the XGBoost model, improving prediction performance and efficiency.

- **Deployment:**
  - Deployed the model on Databricks, enabling real-time predictions via a REST API.

## Technologies Used

- **Databricks:** For managing experiments, hyperparameter tuning, and model deployment.
- **XGBoost:** Chosen for its effectiveness in predictive modeling.
- **Hyperopt:** Used to fine-tune hyperparameters for optimal model performance.
- **REST API:** Facilitates real-time predictions by connecting the model to external applications.

## Notebook
https://github.com/akash-prajapati123/Wine-Quality-Prediction-Model/blob/main/Wine_Quality_Prediction.ipynb
