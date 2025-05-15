# Sonar
# Sonar Rock vs Mine Classification

This project uses a machine learning model to classify sonar signals as either rocks or mines. It is based on the UCI Sonar dataset and demonstrates building and evaluating a logistic regression model using Python and scikit-learn.

---

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)

## Project Description

The goal of this project is to classify sonar signals collected from a rock using a logistic regression classifier. This project covers data preprocessing, model training, evaluation, and prediction on new data.

## Dataset

This project uses the [UCI Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/sonar), which consists of 208 samples with 60 features each. The dataset is included in this repo under the file `sonar_data.csv` (or specify where if you host it somewhere else).

## Installation

1. Clone the repository:
   
git clone https://github.com/Amrutanshu-07/sonar.git
cd sonar

2.  Create and activate a virtual environment:

python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

3. Install dependencies:
   
pip install numpy pandas scikit-learn jupyter


## Usage
jupyter notebook sonar.ipynb

## Model
The project uses Logistic Regression from scikit-learn to classify sonar returns. The model is trained on the sonar dataset and evaluated on a test set, showing good accuracy in distinguishing rocks from mines.

## Results
'R' means Rock
'M' means Mine


