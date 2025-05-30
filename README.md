# Bitcoin Price Prediction with MLFLOW
## Overview

This project aims to predict Bitcoin prices using machine learning models and track experiments with MLflow. It leverages historical Bitcoin price data, preprocesses it, and trains a model to make future price predictions. The project is structured to ensure reproducibility and efficient tracking of model performance.
It also serves as a demonstration of how to integrate and use MLflow for experiment tracking, model logging, and version control in a time series forecasting workflow.

---

## Key Features

- MLflow Integration: Tracks experiments, stores models, and logs key metrics.

- Time-Series Data Processing: Prepares and transforms Bitcoin price data for modeling.

- Machine Learning Model: Uses a neural network to predict future Bitcoin prices.

- Model Loading: Enables loading and inference using mlflow.pyfunc.load_model().

---

## Tech Stack
- Ngrok
- Hyperopt
- Scikit-learn
- Keras
- Mlflow
- Logging

---

## Key Steps in the Project

- Data Collection: Load historical Bitcoin price data from the Tiingo API.

- Data Preprocessing: Normalize and structure data for model training.

- Model Training: Train a neural network model using a limited number of epochs.

- Experiment Tracking with MLflow: Log parameters, metrics, and model artifacts.

- Model Evaluation: Assess performance using validation metrics.

- Model Saving & Loading: Save the trained model and reload it for inference.

---
## Project Limitations

- Limited Training Resources: The model is trained with a small number of epochs due to resource constraints, which may impact prediction accuracy.

- Data Constraints: Performance is dependent on the availability and quality of Bitcoin price data.

- Feature Simplicity: The model does not incorporate external factors like market sentiment or economic indicators.
