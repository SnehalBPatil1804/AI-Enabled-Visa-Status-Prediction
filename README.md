# AI Enabled Visa Status Prediction and Processing Time Estimator

## Milestone 1: Data Collection & Preprocessing
This module establishes the data foundation for predicting visa processing durations.

### Objectives:
- **Build Structured Dataset**: Collected real-world H-1B disclosure data (FY2026 Q1).
- **Target Label Generation**: Created a `Processing_Time_Days` column for regression modeling.
- **Categorical Encoding**: Transformed features like `VISA_CLASS` and `EMPLOYER_STATE` into numerical inputs.

### Project Files:
1. `LCA_Disclosure_Data_FY2026_Q1.xlsx`: Raw input data.
2. `PreProcessing.ipynb`: Script for cleaning and target generation.
3. `cleaned_visa_data.csv`: Final preprocessed file for the AI model.
4. `LICENSE`: MIT standard license.

### Next Steps:
The project will move to **Milestone 2: Exploratory Data Analysis (EDA)** to visualize seasonal trends and feature importance.
