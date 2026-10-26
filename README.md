# Iris Flower Classification using Optimized KNN

A reproducible machine-learning project that classifies Iris flowers into **Setosa, Versicolor, and Virginica** using four numerical measurements and an optimized K-Nearest Neighbors (KNN) workflow.

## Project Overview

This project explores the Iris dataset, compares feature-scaling approaches, and tunes a KNN classifier using cross-validation. Model performance is evaluated on a held-out test set.

## Highlights

- Exploratory data analysis (EDA)
- Stratified train/test split
- Baseline KNN classifier
- Comparison of `StandardScaler` and `MinMaxScaler`
- Cross-validated hyperparameter tuning using `GridSearchCV`
- Evaluation using accuracy, precision, recall, F1-score, and a confusion matrix
- Example flower prediction with class probabilities

## Dataset Features

The model uses four measurements:

- Sepal length
- Sepal width
- Petal length
- Petal width

**Target:** Iris species — Setosa, Versicolor, or Virginica.

## Repository Structure

```text
Iris-Flower-Classification-KNN/
├── IrisFlowerClassificationKNN_Better.ipynb
├── iris.csv
├── requirements.txt
├── README.md
└── index.html
```

## Model Results

On the selected train/test split:

| Metric | Result |
|---|---:|
| Baseline KNN accuracy (k = 3) | 93.33% |
| Tuned KNN accuracy | 93.33% |
| Correct test predictions | 28 / 30 |

The tuned model's confusion matrix shows that all Setosa and Versicolor samples were classified correctly, while two Virginica samples were predicted as Versicolor.

These are results from the selected test split, not a guarantee of performance on unseen data. Hyperparameter tuning did not increase test accuracy on this split.

## Technology Stack

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook
- Git and GitHub

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/PreetiDube/Iris-Flower-Classification-KNN.git
cd Iris-Flower-Classification-KNN
```

### 2. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `IrisFlowerClassificationKNN_Better.ipynb` and run the cells in order. Keep `iris.csv` in the same directory as the notebook.

## Project Links

- **Live project website:** https://preetidube.github.io/Iris-Flower-Classification-KNN/
- **GitHub repository:** https://github.com/PreetiDube/Iris-Flower-Classification-KNN

## Notes on Reproducibility

The reported results correspond to the selected train/test split and notebook configuration. Results may vary with different splits or settings. The notebook should be run from beginning to end to reproduce the analysis.
