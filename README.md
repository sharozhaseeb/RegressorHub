# RegressorHub

This repository contains IPython notebooks that demonstrate linear regression and logistic regression models implemented from scratch in Python.

## Contents

- `linear_regression.ipynb`: Implements linear regression to predict student performance scores. Covers data preprocessing, model training, evaluation, saving and loading.

- `logistic_regression.ipynb`: Implements logistic regression to predict heart disease risk. Covers data preprocessing, model training, evaluation, saving and loading. 

## Usage

The notebooks contain code and explanations for each step. They can be run end-to-end to train models, evaluate them, and save the trained models.

The trained models are saved as Pickle files that can be loaded for inference later.

## Requirements

The notebooks require the following Python packages:

- numpy
- pandas 
- scikit-learn
- matplotlib
- pickle

## References

The implementation is based on concepts from:

- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow by Aurelien Geron
- Introduction to Machine Learning with Python by Andreas C. Muller and Sarah Guido

### Next Steps
- ~~Normalize data(Z-Score, MinMax)~~
- ~~Hyperparameter Tuning~~;
- Adding WandB Logs;
- ~~Maybe a new learning rate?~~;
- ~~Push to hub~~
- ~~save locally~~
