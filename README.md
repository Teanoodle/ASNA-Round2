# ASNA-Round 2 (Portfolio Analysis and Risk Segmentation part)

## Overview
This project contains a comprehensive analysis of student academic performance data, exploring factors that influence student success and conducting predictive modeling. The analysis covers exploratory data analysis, logistic regression modeling, and stress testing of predictive models.

## Project Structure

The analysis is organized in the following sequence:

### 1. EDA.ipynb - Exploratory Data Analysis
- Initial data exploration and visualization
- Statistical summary of student data
- Distribution analysis of key variables (GPA, study habits, etc.)
- Correlation analysis between variables
- Missing value analysis and data quality assessment

### 2. severity_on_4.ipynb - Severity Analysis
- In-depth analysis focusing on four key variables
- Feature importance analysis

### 3. LR.ipynb - Logistic Regression Modeling
- Implementation of logistic regression models
- Interpretation of model coefficients and statistical significance

### 4. stress_test.ipynb - Model Stress Testing
- In GLM model, the output is severity level
- Sensitivity analysis under 4 scenarios
- revaluate the risk segmentation and compare with the original model

## Dataset
The dataset contains student information including:
- See "Glossary.pdf" for detailed variable descriptions

## Dependencies

The project requires the following Python packages:

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import statsmodels.formula.api as smf
import statsmodels.api as sm
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score, roc_auc_score, confusion_matrix
```

Install dependencies using:
```bash
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn
```

## Getting Started

1. **Clone or download** the project files
2. **Install dependencies** as listed above
3. **Run the notebooks in sequence**:
   - Start with `EDA.ipynb` for data exploration
   - Proceed to `severity_on_4.ipynb` for classification analysis
   - Continue with `LR.ipynb` for logistic regression modeling
   - Finish with `stress_test.ipynb` for model validation


## Usage

Each notebook is self-contained and can be run independently, but following the recommended sequence will provide the most comprehensive understanding of the analysis.

## Results

The analysis provides insights into:
- Key factors influencing student academic performance
- Predictive models for student success classification
- Model performance metrics and validation results
- Recommendations based on statistical findings

## License

This project is for academic/analytical purposes. Please ensure proper data privacy and ethical considerations when working with student data.
