# Task 8: Basic Classification

Classifies iris flowers (setosa, versicolor, virginica) using Scikit-Learn **Logistic Regression**.

## Files
- `classification.ipynb`: full notebook (load data, split, train, evaluate, predict)
- `iris.csv`: the dataset (saved by the notebook)
- `confusion_matrix.png`: saved after running

## How to run
```bash
pip install pandas matplotlib scikit-learn jupyter
jupyter notebook classification.ipynb      # then Run All
```

## Key results
- Dataset: 150 samples, 4 features, 3 classes, no missing values.
- 80/20 stratified train/test split.
- **Test accuracy: 96.67%** (29 of 30 test flowers correct; the one miss is between versicolor and virginica). Re-check this against your own notebook output.
