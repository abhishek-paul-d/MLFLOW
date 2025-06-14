# MLFlow Projects

This repository contains MLFlow experiments for different machine learning tasks.

## Project Structure

```
d:/ML/MLFLOW/
├── 1-MLProject/
│   ├── experiments.ipynb - Iris classification with logistic regression
│   ├── get-started.ipynb - [Error reading file]
│   └── mlartifacts/ - MLFlow artifacts
├── 2-HousePricePred/
│   └── houspriceprediction.ipynb - California housing price prediction with random forest
└── 3-DLMLFLOW/
    └── starter.ipynb - Wine quality prediction with ANN hyperparameter tuning
```

## Notebook Details

### 1-MLProject/experiments.ipynb
- Implements logistic regression models for iris dataset classification
- Tracks experiments with MLflow including:
  - Model parameters
  - Accuracy metrics
  - Model signatures
- Demonstrates model registry and inference

### 2-HousePricePred/houspriceprediction.ipynb
- Predicts California housing prices using random forest regression
- Performs hyperparameter tuning with GridSearchCV
- Tracks experiments with MLflow including:
  - Best hyperparameters
  - Mean squared error metrics
  - Model registration

### 3-DLMLFLOW/starter.ipynb
- Predicts wine quality using artificial neural networks
- Performs hyperparameter optimization with Hyperopt
- Tracks experiments with MLflow including:
  - Learning rate and momentum parameters
  - RMSE metrics
  - TensorFlow model logging

## Requirements
- Python 3.10
- MLflow
- Scikit-learn
- TensorFlow/Keras (for starter.ipynb)
- Hyperopt (for starter.ipynb)

## Setup
1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Start MLflow tracking server:
```bash
mlflow ui
```

3. Run notebooks in order to see MLflow tracking in action.
