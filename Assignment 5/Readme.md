# BDL Assignment 5: Tracking Model Building Experiments with MLFlow

This repository folder contains the code and instructions for the BDL (Big Data and Learning) Assignment 5, which focuses on tracking model-building experiments using the MLFlow platform.

## Description

The assignment aims to build several neural network models for MNIST digit classification with different model configuration settings. Each configuration setting will show different patterns in model-building performance measurements over every learning epoch. The goal is to compare the model performance trends and understand the impact of model configuration settings.

Instead of manually coding for data collection and visualization, MLFlow automatically tracks the metrics and parameters during the model-building process.

## Files

1. `A05-Tracking a Model building experiment in MLFlow.pdf`: This file contains the assignment instructions and tasks.
2. `MM20B007 BDL Assignment 5.ipynb`: This file contains the Jupyter Notebook code for building the classification models with different parameter settings and logging the experiments using MLFlow.

## Tasks

The main tasks of the assignment are:

1. Modify the code to log metrics (loss, accuracy) using `mlflow.autolog()` and `mlflow.log_metrics()`.
2. Modify the code to log parameters (network configuration, learning rate, optimizer, regularization, etc.) using `mlflow.autolog()` and `mlflow.log_param()`.
3. Use the `with mlflow.start_run()` construct to run the model build for each configuration, creating a new entry in MLflow for each run.
4. Configure the entire MNIST experiment as an experiment, with each neural configuration becoming a sub-experiment.
5. Visualize and compare the performance numbers using the "Compare" button in the MLflow UI, taking snapshots of the comparison plots.
6. Compare models across experiments and take snapshots of the plots.

## Requirements

- Python
- TensorFlow
- MLFlow

## Usage

1. Clone the repository
2. Install the required dependencies
3. Navigate to the project directory
4. Run the Jupyter Notebook `MM20B007 BDL Assignment 5.ipynb`
5. Follow the instructions in the notebook and the assignment file to complete the tasks
6. Once the notebook is ready, run the entire code. Once done, a new folder (ML runs) will appear where the code is saved.
7. Open PowerShell at the same location where the ML runs folder is and write the following command "mlflow ui -p 1234" to open the MLflow UI.
8. View and analyze the logged experiments in the MLflow UI.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
