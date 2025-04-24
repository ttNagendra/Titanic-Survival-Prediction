# Titanic Survival Prediction Project

## Project Overview
This project implements a machine learning model to predict passenger survival on the Titanic disaster with a target accuracy of 90%. The model uses passenger information such as age, gender, ticket class, and other features to make predictions.

## Objectives
- Develop an accurate machine learning model for Titanic survival prediction
- Implement comprehensive data preprocessing and feature engineering
- Achieve high prediction accuracy (target: 90%)
- Provide clear visualization of data insights
- Create a reproducible machine learning pipeline

## Project Structure
```
├── tested.csv                    # Input dataset
├── titanic_survival_prediction.ipynb  # Main Jupyter notebook
├── titanic_model.pkl            # Saved trained model
└── feature_importance.csv       # Feature importance analysis
```

## Requirements
- Python 3.7+
- Required Python packages:
  - pandas
  - numpy
  - scikit-learn
  - seaborn
  - matplotlib
  - joblib

## Setup and Installation
1. Clone this repository or download the project files
2. Install required Python packages:
```powershell
pip install pandas numpy scikit-learn seaborn matplotlib joblib
```

## Running the Project
1. Navigate to the project directory
2. Open the Jupyter notebook:
```powershell
jupyter notebook titanic_survival_prediction.ipynb
```
3. Run all cells in the notebook sequentially

## Project Steps
1. **Data Loading and Exploration**
   - Load the Titanic dataset
   - Examine basic statistics and missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualize feature distributions
   - Analyze relationships between features
   - Identify patterns in survival rates

3. **Data Preprocessing**
   - Handle missing values
   - Create new features
   - Encode categorical variables
   - Scale numerical features

4. **Model Development**
   - Implement RandomForest Classifier
   - Create preprocessing pipeline
   - Train model on prepared data

5. **Model Evaluation**
   - Calculate accuracy and other metrics
   - Generate classification report
   - Analyze feature importance

## Model Performance
The model's performance metrics (accuracy, precision, recall) are displayed in the notebook after training. The feature importance analysis is saved to 'feature_importance.csv'.

## Files Generated
- `titanic_model.pkl`: Saved trained model
- `feature_importance.csv`: Analysis of feature importance

## Author
[Your Name]

## License
This project is open source and available under the MIT License.
