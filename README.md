# DecisionTree_Visualization

This project demonstrates how to build and visualize a **Decision Tree classifier** using Python and scikit-learn.  
It uses a small categorical dataset (“Buys_Computer”) and walks through preprocessing, training, visualization, and interpretation.

---

## 📂 Repository Contents
- `DecisionTree_Visualization.ipynb` — Jupyter notebook with all code, visualizations, and explanations.

---

## ⚙️ Requirements
- Python 3.9+  
- Packages:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `jupyter`

Install with:
```bash
pip install pandas scikit-learn matplotlib jupyter

## 📊 Dataset
Features:
Age (<=30, 31–40, >40)
Income (Low, Medium, High)
Student (Yes/No)
Credit_Rating (Fair/Excellent)

Target:
Buys_Computer (Yes/No)

🛠️ Workflow:
Preprocessing: one-hot encoding of categorical features
Model: DecisionTreeClassifier(criterion="entropy", max_depth=3)
Visualization:
Tree structure (sklearn.tree.plot_tree)
Feature importances (bar chart)
Prediction on a sample input
