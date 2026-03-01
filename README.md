# Stylometry – SemEval 2026 Task 13

This repository contains our solution for SemEval-2026 Task 13 (Machine-Generated Code Detection).

## Approach
- Character-level TF-IDF features
- Structural features (length, punctuation, comments, etc.)
- Clustering-based mixture of experts
- Logistic Regression + Naive Bayes ensemble
- Threshold calibration for macro F1

## How to run
1. Upload kaggle.json file in google collab or place it in your local environment. This can be got from the kaggle website
2. Run notebook:
   semeval2026_task13_solution.ipynb
   
## Requirements
- Python 3.10
- scikit-learn
- pandas
- numpy
