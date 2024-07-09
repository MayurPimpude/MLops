# MLOps with ElasticNet Model

This repository contains an implementation of the ElasticNet regression model, demonstrating MLOps practices for model training, evaluation, and hyperparameter tuning.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)

## Introduction
The project showcases the use of ElasticNet regression, a combination of L1 and L2 regularization, for predicting continuous outcomes. The implementation emphasizes the principles of MLOps, ensuring reproducibility, scalability, and efficient model management.

## Features
- Implementation of ElasticNet regression
- Hyperparameter tuning for alpha and l1_ratio
- Performance evaluation with metrics: RMSE, MAE, and R2

## Setup
To set up the project, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/MayurPimpude/MLops.git
    cd MLops
    ```

2. **Install Dependencies**
    Ensure you have Python and the required dependencies installed.
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Run the `example.py` script to train and evaluate the ElasticNet model. You can pass `alpha` and `l1_ratio` as command-line arguments.

```bash
python example.py
```
## Results
The performance of the ElasticNet model is evaluated using RMSE, MAE, and R2 metrics. Results will vary based on the input parameters. The example outputs above show the evaluation metrics for different parameter settings.
