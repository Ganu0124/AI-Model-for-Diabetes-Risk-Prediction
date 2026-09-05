# AI Model for Diabetes Risk Prediction and Early Diagnosis.



## Features
- Diabetes risk prediction
- Early diagnosis support
- Constraint Satisfaction Problem (CSP) based analysis
- Automated risk classification
- Data visualization using charts and heatmaps
- Risk score generation
- Explainable AI results

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset Attributes
The dataset contains:
- datetime
- patient_id
- code
- value

## Risk Categories
- Low Risk
- Medium Risk
- High Risk

## Project Workflow
1. Load dataset
2. Preprocess data
3. Apply CSP constraints
4. Calculate risk scores
5. Classify risk levels
6. Generate visualizations
7. Export final results

## Constraint Rules
The model evaluates:
- High code values
- High measurement values
- Frequent patient visits
- Odd-time hospital visits
- Abnormal value-to-code ratio

## Visualizations
The project generates:
- Constraint activation graph
- Risk distribution bar chart
- Pie chart analysis
- Heatmap correlation analysis

## Output Files
- final_output.csv
- advanced_csp_output.csv

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
