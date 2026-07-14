# Fundamentals of Machine Learning Project

## Overview
This project applies various machine learning techniques to predict English Premier League match outcomes using first-half in-game statistics. The primary goal was to evaluate the predictive performance of different models, identify the most important features for prediction, and assess per-team accuracy. This was completed as the term project for a fundamentals of machine learning course.

## Repository Contents
*   **`DSCI_3415_Project.ipynb`**: The main Jupyter Notebook containing the complete analysis, model training, and evaluation.
*   **`dsci_3415_project.py`**: The Python script version of the project code.
*   **`DSCI 3415 Project Report.docx.pdf`**: The final project report detailing the methodology, results, and conclusions.
*   **`DSCI 3415 Presentation.pptx`**: The slide deck for the project presentation.
*   **`matches.zip`**: The dataset containing match information.
*   **`teams.json`**: JSON file with team details.

## Key Methods and Techniques
*   **Machine Learning Models**: Implemented and compared three classification algorithms:
    *   **Logistic Regression**
    *   **Random Forest**
    *   **K-Nearest Neighbors (KNN)**
*   **Model Evaluation**: Performance was rigorously evaluated across 10 randomized trials to ensure robustness.
*   **Feature Importance Analysis**: Investigated which first-half statistics (e.g., shots, possession, fouls) were most vital in predicting the final outcome.
*   **Per-Team Accuracy Visualization**: Analyzed model performance on a per-team basis to identify strengths and weaknesses.

## How to Reproduce This Work
1.  Clone this repository to your local machine.
2.  Ensure you have Python and Jupyter Notebook installed.
3.  Install required libraries: `pandas`, `scikit-learn`, `matplotlib`, and `seaborn`.
4.  Extract the `matches.zip` file to access the dataset.
5.  Open and run the `DSCI_3415_Project.ipynb` notebook to reproduce the analysis.
