# ME F321 – Machine Learning Labs

Laboratory notebooks and task sheets for **ME F321** (BITS Pilani, Pilani Campus).

**Author:** [baghazzz](https://github.com/baghazzz)

## Structure

| Lab | Topic | Datasets | Contents |
|-----|-------|----------|----------|
| [Lab 6](lab6_tree_models/) | Decision Trees, Random Forest, Gradient Boosting | Sensorless Drive Diagnosis, AI4I Predictive Maintenance | `notebooks/` |
| [Lab 7](lab7_naive_bayes_svm/) | Gaussian Naive Bayes, SVM (OvO / OvR) | Steel Plates Faults (UCI id 198), predictive maintenance | `notebooks/`, `tasks/` |
| [Lab 8](lab8_knn_neural_networks/) | kNN, Keras neural network | `glass.csv`, Steel Plates Faults | `notebooks/`, `tasks/` |

Each lab folder holds `notebooks/` (solutions) and `tasks/` (the assignment PDF, where available).

## Setup

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Lab 8 Task 1 expects `glass.csv` in `lab8_knn_neural_networks/data/` (or adjust the path in the notebook).
