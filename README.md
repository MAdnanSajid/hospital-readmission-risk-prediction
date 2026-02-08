# Hospital Readmission Risk Prediction

## Project Overview
This project aims to predict hospital readmission risk using patient demographic and clinical data. By analyzing public healthcare datasets from NHS Digital and the Office for National Statistics (UK), we explore trends, patterns, and features that can help build predictive machine learning models.

## Dataset
The dataset is available in the `data/` folder:
- `hospital_readmission_cleaned.xlsx` – Cleaned dataset used for EDA and modeling.
- Data collected from NHS hospitals across the United Kingdom.

### Features include:
- Demographics: Age, Sex
- Clinical: Diagnosis, Method, Indicator values
- Statistical intervals: CI (95%, 99.8%)
- Other: Numerator, Denominator, Expected, Banding, Warnings

## Exploratory Data Analysis (EDA)
The `eda/` folder contains analysis and visualizations to understand the dataset, detect anomalies, and prepare features for modeling.

- **notebooks/eda_hospital_readmission.ipynb** – Jupyter notebook with step-by-step EDA.
- **plots/** – Folder containing all visualizations from EDA.

**Key EDA Steps:**
1. Data Loading and Inspection
2. Univariate Analysis – Distribution of numerical and categorical features
3. Bivariate Analysis – Relationships between features and target
4. Correlation Analysis – Numeric feature correlations
5. Feature Insights – Identifying important variables for prediction
6. Next Steps / Observations – Highlight features for modeling, missing values, and encoding needs

## How to Use
1. Open the notebook in `notebooks/eda_hospital_readmission.ipynb`.
2. Run cells sequentially to reproduce the EDA analysis and plots.
3. Use insights for feature engineering and predictive modeling.

## Next Steps
- Handle missing values and outliers
- Encode categorical variables
- Feature selection for model training
- Model building and evaluation
