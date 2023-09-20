# Credit Card Default Analysis

## Introduction
This repository contains an analysis of a dataset from UCI that examines credit card defaults. The goal is to understand the dataset's characteristics, perform exploratory data analysis, and build predictive models to assess default risk.

## Dataset
The dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

Key features include:
- Default payment status (Yes = 1, No = 0)
- Amount of given credit
- Gender, Education, Marital Status, Age
- History of past payment (from April to September 2005)
- Amount of bill statement (from April to September 2005)
- Amount of previous payment (from April to September 2005)

## Analysis Overview
The Jupyter notebook `Credit_Default_Analysis.ipynb` provides a detailed analysis, which includes:
- Initial data exploration and visualization.
- Data preprocessing steps.
- Building and evaluating predictive models, including a Random Forest classifier.

## Model Results
The Random Forest model was utilized as a starting point for this analysis. Key results from this model are:
- Accuracy of approximately 81.36%.
- ROC AUC Score of around 64.21%.
- The model demonstrated good precision for non-default cases (84%) but had a lower recall for default cases (34%).

## Further Exploration
While the initial results are promising, there's potential for improvement. Here are some suggested next steps:
- **Hyperparameter Tuning**: Fine-tune the model parameters to enhance performance.
- **Feature Engineering**: Explore the creation of new features or modification of existing ones to provide the model with more predictive power.
- **Model Exploration**: Experiment with other machine learning algorithms such as gradient boosting, neural networks, or ensemble methods.
- **Class Imbalance**: Address the imbalance in the target variable using techniques like SMOTE, ADASYN, or undersampling.
- **Model Interpretability**: Use tools like SHAP or LIME to understand model predictions better.

## Instructions
To run the notebook:
1. Ensure you have Jupyter Notebook or Jupyter Lab installed.
2. Install necessary Python libraries, including pandas, matplotlib, seaborn, and scikit-learn.
3. Clone this repository and navigate to the directory.
4. Start Jupyter Notebook or Jupyter Lab and open `Credit_Default_Analysis.ipynb`.
5. Run the notebook cells in sequence.

## Notes
This analysis is intended for educational purposes. Suggestions and contributions are welcome!

## References
- Dataset source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
