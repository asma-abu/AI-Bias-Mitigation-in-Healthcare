# AI Bias Mitigation in Healthcare Diagnostics

## Overview

This project demonstrates the application of machine learning and responsible AI techniques to investigate racial bias in the diagnosis of Age-related Macular Degeneration (AMD). Using a healthcare dataset, the project evaluates model performance before and after applying bias mitigation techniques to improve fairness across demographic groups.

## Repository Contents

- **AI_Bias_Mitigation_AMD_Diagnostics.ipynb** – Jupyter notebook containing the complete machine learning workflow.
- **data_summary_amd.csv** – Dataset used for model development and evaluation.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- AIF360

## Methodology

- Loaded and explored the healthcare dataset.
- Cleaned and prepared data for machine learning.
- Encoded categorical variables and created a binary target variable.
- Split the dataset into training, validation, and test sets.
- Trained a Logistic Regression classification model.
- Evaluated model performance using accuracy and classification metrics.
- Measured disparate impact across protected demographic groups.
- Applied the Reweighing algorithm using AIF360 to mitigate bias.
- Compared fairness metrics and model performance before and after mitigation.

## Skills Demonstrated

- Machine Learning
- Data Preprocessing
- Classification
- Model Evaluation
- Responsible AI
- Fairness Analysis
- Bias Mitigation
- Python Programming
- Data Analysis

## Learning Outcomes

This project strengthened my experience in:

- Building end-to-end machine learning workflows.
- Applying fairness metrics to evaluate AI systems.
- Using AIF360 to implement bias mitigation techniques.
- Analyzing healthcare datasets using Python.
- Communicating model performance through quantitative evaluation.

## Running the Project

1. Clone or download this repository.
2. Open `AI_Bias_Mitigation_AMD_Diagnostics.ipynb` in Jupyter Notebook or Google Colab.
3. Ensure `data_summary_amd.csv` is located in the same working directory as the notebook.
4. Run the notebook from top to bottom to reproduce the analysis.

## Disclaimer

This project was completed for academic and research purposes to explore fairness in machine learning models. It does not constitute a clinical diagnostic tool.
