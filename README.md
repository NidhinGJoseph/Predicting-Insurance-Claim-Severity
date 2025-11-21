Insurance Claim Severity – Machine Learning Model

This project focuses on building a machine-learning pipeline to analyze and predict insurance claim severity using a structured dataset.
The notebook walks through essential steps including data cleaning, preprocessing, feature engineering, and model building.

Project Workflow
1. Data Loading & Setup
Imported core Python libraries (pandas, numpy, scikit-learn).
Installed and used category_encoders for handling categorical variables.
Loaded raw insurance claims data.

2. Data Cleaning
Dropped irrelevant columns.
Inspected missing values and handled them systematically.
Converted numerical and datetime columns to proper formats.

3. Feature Preprocessing
Treated missing values for:
  Numeric features
  Categorical features
  Datetime-based components
Encoded categorical variables using appropriate encoding techniques.

4. Exploratory Data Analysis (optional section depending on notebook)
Inspected distributions and value counts.
Identified key patterns in claim severity.

5. Model Development
Built machine learning models for predicting insurance claim severity.
Trained and evaluated using standard metrics.

📂 Repository Structure
📁 Insurance-Claim-Severity
 ├── INSURANCE.ipynb      # The main notebook
 ├── Insurance_Claims.csv # Dataset
 └── README.md            # Project documentation

Requirements

Install dependencies:
  pip install pandas numpy scikit-learn category_encoders

How to Run
Clone the repository
Place the dataset in the same folder as the notebook
Run all cells in order to reproduce the analysis and model results

Project Outcome
The notebook demonstrates:
  A complete end-to-end workflow
  Clean preprocessing pipeline
  A functioning prediction model
  Readable, interview-friendly ML project structure
