# Plant Classifier

## Overview
The "Plant Classifier" project aims to classify agricultural plants into different categories based on their dimensional and shape factors. The dataset contains various features that describe the physical characteristics of the plants, and the goal is to predict the class or category a given plant belongs to.

## Table of Contents
- [Data Description](#data-description)
- [Setup and Installation](#setup-and-installation)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Results](#results)
- [Future Work](#future-work)
- [Contact](#contact)

## Data Description
The dataset contains the following features:
- Area
- Perimeter
- MajorAxisLength
- DFactor1 to DFactor9
- ShapeFactor1 to ShapeFactor4
- Class (Target Variable)

The target variable, `Class`, contains categories like "BA", "BO", "CA", "DE", "HO", "SE", and "SI".

## Setup and Installation
1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to execute the project.

## Data Preprocessing
The data underwent several preprocessing steps:
- Handling missing values
- Feature scaling using `StandardScaler`
- Encoding categorical variables using `LabelEncoder`

## Model Training and Evaluation
Several classification algorithms were applied to the preprocessed data:
- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machine Classifier
- k-Nearest Neighbors Classifier
- Gradient Boosting Classifier

Each model's performance was evaluated using accuracy, precision, recall, F1 score, and ROC AUC.

## Hyperparameter Tuning
Hyperparameter tuning was performed for the `ExtraTreesClassifier` using `GridSearchCV`. The best parameters were selected based on cross-validation results.

## Results
The Support Vector Machine (SVM) classifier achieved the highest accuracy among all the models. The confusion matrix and classification report provided detailed insights into the model's performance for each class.

## Future Work
- Explore other classification algorithms and ensemble methods.
- Implement feature engineering to improve model performance.
- Deploy the model as a web application for real-time plant classification.

## Contact
For any queries or feedback, please reach out to:
- Email: [rk.pani2002@gmail.com](mailto:rk.pani2002@gmail.com)
