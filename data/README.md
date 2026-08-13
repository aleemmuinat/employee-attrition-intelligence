# Data

## Dataset

This project uses the **IBM HR Analytics Employee Attrition & Performance Dataset**, sourced from Kaggle.

### Dataset Source

[IBM HR Analytics Employee Attrition & Performance — Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

The dataset was created by IBM data scientists as a fictional HR analytics dataset for exploring employee attrition and related workforce patterns.

## Dataset Overview

The dataset contains employee-level information covering:

- Demographics
- Job characteristics
- Compensation
- Job satisfaction
- Work-life balance
- Career progression
- Work experience
- Overtime
- Employee attrition

### Dataset Size

- **1,470 employees**
- **35 variables in the original dataset**
- Binary employee attrition target

### Target Variable

The original `Attrition` variable contains:

- `Yes` — Employee left
- `No` — Employee stayed

For machine learning, the target was transformed into:

- `0` — Stayed
- `1` — Left

## Data Availability

The raw dataset is **not included in this repository**.

The analysis was performed using the dataset obtained from Kaggle. The repository focuses on the analytical workflow, visualizations, model evaluation, explainability, and business insights rather than redistributing the source dataset.

## Reproducibility

To reproduce the analysis, obtain the dataset from the Kaggle source above and make it available locally before running the analysis notebook.

The notebook documents the preprocessing, feature engineering, exploratory analysis, statistical analysis, machine learning, threshold optimization, and model explainability workflow used in this project.
