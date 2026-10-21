# Iris Flower Classification using Optimized KNN

A reproducible machine-learning project that classifies Iris flowers into setosa, versicolor, and virginica from four measurements.

## Highlights
- Exploratory data analysis
- Stratified train/test split
- Baseline KNN model
- StandardScaler and MinMaxScaler comparison
- Cross-validated hyperparameter tuning with GridSearchCV
- Test-set accuracy, classification report, and confusion matrix
- Example prediction with class probabilities

## Files
- `IrisFlowerClassificationKNN_Better.ipynb` — notebook
- `iris.csv` — clean dataset
- `requirements.txt` — dependencies

## Run locally
```bash
python -m pip install -r requirements.txt
jupyter notebook
```
Open the notebook and run all cells. Keep `iris.csv` beside the notebook.

## Notes
The reported score is the measured result for the chosen test split. Accuracy is not guaranteed to improve on every split, and 100% accuracy should not be assumed.
