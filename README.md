# Task 7: Support Vector Machines (SVM)

This project implements Support Vector Machines (SVM) for both linear and non-linear classification using the **Breast Cancer Wisconsin** dataset from `scikit-learn`. It follows the task requirements from your internship assignment.

## 📌 Objectives
- Load and prepare a dataset for binary classification.
- Train SVM with **Linear** and **RBF** kernels.
- Visualize decision boundaries using 2D datasets.
- Tune hyperparameters (**C** and **gamma**) using GridSearchCV.
- Evaluate performance with cross-validation.

## 🛠 Tools Used
- Python 3
- NumPy
- Matplotlib
- scikit-learn

## 📂 Files
- `Task 7.ipynb`: Jupyter notebook with the step-by-step implementation.
- - `README.md`: This file.

## 🚀 How to Run
1. Install dependencies:
```bash
pip install scikit-learn numpy matplotlib
```

2. Open the notebook:
```bash
jupyter notebook "Task 7.ipynb"
```

3. Run all cells to:
   - Train Linear and RBF SVMs
   - Tune hyperparameters
   - Visualize decision boundaries

## 📊 Dataset
Using the **Breast Cancer Wisconsin** dataset available directly from `sklearn.datasets`.
## 📈 Example Results
| Model       | Test Accuracy | CV Mean Accuracy |
|-------------|--------------|------------------|
| Linear SVM  | ~0.95         | ~0.96            |
| RBF SVM     | ~0.97         | ~0.97            |
