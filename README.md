# Insurance Claim Prediction

This repository contains a Streamlit web application that predicts insurance claim amounts and claim class based on various input features. The application uses trained machine learning models to make these predictions.

## Features
The app allows users to input details about a person such as:
- **Age**: Numerical input.
- **Weight**: Numerical input.
- **Blood Pressure**: Numerical input.
- **BMI**: Numerical input.
- **Number of Dependents**: Selection box (0 to 5).
- **Sex**: Selection box (Male/Female).
- **Smoker**: Selection box (Yes/No).
- **Diabetes**: Selection box (Yes/No).
- **Regular Exercise**: Selection box (Yes/No).
- **Hereditary Diseases**: Selection box of various diseases.
- **City**: Selection box of cities across the US.
- **Job Title**: Selection box with job categories.

## How It Works
- The user provides input values for the aforementioned features.
- The app then uses two pre-trained models:
  - **RandomForestModel.pkl**: Predicts the insurance claim amount.
  - **RandomForestClassifier.pkl**: Classifies the claim category.
- The predicted results are displayed on the interface after clicking the "Predict" button.

## Models Used
1. **Random Forest Regressor** for predicting the insurance claim amount.
2. **Random Forest Classifier** for predicting the claim class (e.g., whether a claim will be approved or denied).

## Installation

To run the app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/GhufranBarcha/Insurance-Claim-Prediction.git
