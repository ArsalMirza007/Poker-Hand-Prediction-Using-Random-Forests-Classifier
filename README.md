# Poker-Hand-Prediction-Using-Random-Forests-Classifier

### Screenshots:
![Datafram](https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier/assets/121928372/05e62a75-09db-4b54-930e-4af0e2c9190b)
![data after preprocessing](https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier/assets/121928372/041607d1-7c67-492a-8eb5-c48efbbd0e4c)
![base class](https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier/assets/121928372/d451a17a-9404-4c02-8747-75147cbfc131)
![roc curve](https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier/assets/121928372/ce785f60-47df-46d6-bd06-62c42f45ce94)
![class prediction](https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier/assets/121928372/76b19823-a803-4d3b-883d-08ea8090ad87)
![classification report](https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier/assets/121928372/f53abc6a-8264-4185-95da-5ec1cdcad255)


# Poker Hand Prediction using Machine Learning

Welcome to the Poker Hand Prediction repository! This repository contains code and data for training, evaluating, and saving machine learning models for predicting poker hands using various classifiers such as Random Forests, MLP, SVM, and others.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Saving the Model](#saving-the-model)
- [Contributing](#contributing)

## Overview

This project focuses on training machine learning models to predict poker hands using a dataset of poker hands. The data includes features representing the suits and ranks of cards in a poker hand and a target label indicating the type of poker hand.

The repository provides scripts for:

- Loading and pre-processing the data.
- Training machine learning models using different classifiers.
- Evaluating model performance using metrics such as accuracy, ROC curves, and classification reports.
- Saving trained models for future use.

## Data

The dataset used in this project is in the form of a CSV file (`/content/poker_hand_test.data`) and is loaded into a pandas DataFrame (`poker_df`). The dataset includes:

- Features representing the suits and ranks of cards in poker hands.
- A target label (`hand`) indicating the type of poker hand.

## Usage

1. **Clone the repository**: Clone this GitHub repository to your local machine.

    ```bash
    git clone https://github.com/ArsalMirza007/Poker-Hand-Prediction-Using-Random-Forests-Classifier.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd Poker_Hand_Prediction_Using_Random_Forests.ipynb
    ```

3. **Install dependencies**: Install the required Python libraries using pip.

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the notebook**: Load the Jupyter notebook and follow the instructions to train and evaluate models, plot ROC curves, and save the trained model.

## Model Training

The repository provides scripts for training machine learning models using classifiers such as MLP, Random Forests, SVM, and others on the poker hand dataset.

## Evaluation

Model performance can be evaluated using metrics such as accuracy, ROC curves, and classification reports. The repository provides scripts to visualize these metrics.

## Saving the Model

You can save the trained model for deployment using the provided scripts with `joblib`. This allows you to reuse the model later without retraining it.

## Contributing

Contributions to this project are welcome! Feel free to open issues, create pull requests, or provide feedback.
