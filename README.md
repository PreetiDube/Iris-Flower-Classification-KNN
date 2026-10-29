# Iris Flower Classification using Optimized KNN 🌸

A machine learning project that classifies Iris flowers into **Setosa, Versicolor, and Virginica** using four flower measurements and a K-Nearest Neighbors (KNN) classifier.

🔗 **[Live Website](https://preetidube.github.io/Iris-Flower-Classification-KNN/)** | **[GitHub Repository](https://github.com/PreetiDube/Iris-Flower-Classification-KNN)**

## 📌 Project Overview

This project explores the Iris dataset, performs exploratory data analysis, compares feature-scaling methods, and tunes a KNN classifier using cross-validation. The selected model is evaluated on a held-out test set.

## ✨ Key Features

- Exploratory Data Analysis (EDA)
- Stratified train/test split
- Baseline KNN classifier
- StandardScaler and MinMaxScaler comparison
- Hyperparameter tuning using GridSearchCV
- Evaluation using accuracy, precision, recall, F1-score, and a confusion matrix
- Example flower prediction with class probabilities

## 🌼 Dataset

The model uses four input features:

- Sepal length
- Sepal width
- Petal length
- Petal width

**Target classes:** Setosa, Versicolor, and Virginica.

## 🛠️ Technology Stack

- **Language:** Python
- **Data analysis:** Pandas, NumPy
- **Machine learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab
- **Version control:** Git, GitHub

## 📊 Model Results

Results from the current notebook run and selected test split:

| Metric | Result |
|---|---:|
| Baseline KNN test accuracy (k = 3) | 93.33% |
| Tuned KNN test accuracy | 93.33% |
| Correct test predictions | 28 out of 30 |

Hyperparameter tuning did not increase test accuracy on this particular split.

### Confusion Matrix Summary

- All Setosa test samples were classified correctly.
- All Versicolor test samples were classified correctly.
- Eight out of ten Virginica test samples were classified correctly.
- Two Virginica samples were predicted as Versicolor.

These results describe one test split and do not guarantee the same performance on new data.

## 📂 Project Structure

```text
Iris-Flower-Classification-KNN/
├── IrisFlowerClassificationKNN_Better.ipynb
├── iris.csv
├── requirements.txt
├── README.md
└── index.html
```

## 🚀 Run the Project Locally

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

## 📁 Project Links

- **Live Website:** https://preetidube.github.io/Iris-Flower-Classification-KNN/
- **Source Code and Notebook:** https://github.com/PreetiDube/Iris-Flower-Classification-KNN

## 📝 Reproducibility Notes

The reported metrics correspond to the current notebook configuration and selected train/test split. Results may vary with different splits or model settings. Run the notebook from beginning to end to reproduce the analysis.

## Author

**Preeti Dube**

- GitHub: [PreetiDube](https://github.com/PreetiDube)
- Project Repository: [Iris Flower Classification using Optimized KNN ](https://github.com/PreetiDube/Iris-Flower-Classification-KNN)

