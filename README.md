# Indian_Kids_Screen_Time_Analysis
Data science project analyzing screen time impact on Indian kids

# Indian Kids Screen Time Analysis

## Project Overview
This project analyzes the impact of screen time on Indian children using a dataset of 9,712 entries and 13 columns. The goal was to predict whether kids exceeded recommended screen time limits.

## Methodology
- **Exploratory Data Analysis (EDA)**: Visualized screen time distributions and health impacts (e.g., Poor Sleep, Eye Strain).
- **Statistical Analysis**: Conducted t-tests (e.g., tablet vs. smartphone, p=0.0000) and chi-square tests (e.g., health impacts, p=0.0000).
- **Modeling**: Built a Random Forest model with 96% accuracy, validated by cross-validation (0.96 +/- 0.01), and tuned with balanced weights (class 0 recall 0.99).

## Results
- Accuracy: 0.96
- Class 0 (Not Exceeded): Recall = 0.99, F1 = 0.88
- Class 1 (Exceeded): F1 = 0.98
- Key Features: Avg_Daily_Screen_Time_hr, Poor Sleep, Device_Tablet

## Files
- `Indian_Kids_Screen_Time.ipynb`: Main Jupyter Notebook
- `rf_model_tuned.pkl`: Saved tuned model
- `Indian_Kids_Screen_Time.csv`: Dataset 

## How to Run
1. Clone the repository: `git clone <repository-URL>`
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib joblib`
3. Open and run the notebook.

