# Multi-Class Benchmark Classification Pipeline

## Overview
This project compares Logistic Regression and Decision Tree classifiers using the Iris dataset for the Datheon ML & DS task.

## Objectives
- Explore the Iris dataset.
- Split the data into training and testing sets using an 80:20 ratio.
- Standardize numerical features.
- Train Logistic Regression and Decision Tree classifiers.
- Evaluate accuracy, macro precision, macro recall, and macro F1-score.
- Visualize confusion matrices and decision boundaries.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

## Project Files
- `iris.csv` — Original dataset.
- `iris_classification_pipeline.ipynb` — Complete notebook, code, results, and visualizations.
- `iris_dataset.csv` — Saved dataset copy.
- `model_comparison.csv` — Model evaluation metrics.

## How to Run
1. Install Python 3.
2. Install dependencies:
   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter ipykernel`
3. Open `iris_classification_pipeline.ipynb` in VS Code or Jupyter Notebook.
4. Run the notebook cells from top to bottom.

## Evaluation
Both classifiers are evaluated on a held-out test set using accuracy, macro precision, macro recall, and macro F1-score. The notebook includes confusion matrix heatmaps and decision boundary plots.

## Learning Outcomes
This project demonstrates data exploration, feature scaling, supervised classification, model evaluation, confusion matrix interpretation, and decision boundary visualization.