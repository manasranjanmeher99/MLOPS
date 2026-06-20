# MLflow Experiment Tracking with Logistic Regression

## 📌 Overview

This project demonstrates how to use MLflow for experiment tracking in a Machine Learning workflow.

A Logistic Regression model is trained on a synthetic imbalanced classification dataset generated using Scikit-Learn. The experiment parameters, metrics, and trained model are logged and visualized through the MLflow Tracking UI.

---

## 🚀 Features

- Synthetic Dataset Generation
- Imbalanced Binary Classification
- Logistic Regression Model
- Model Evaluation
- MLflow Experiment Tracking
- Parameter Logging
- Metric Logging
- Model Logging
- Experiment Visualization

---

## 🛠️ Tech Stack

- Python
- NumPy
- Scikit-Learn
- MLflow
- Jupyter Notebook

---

## 📂 Project Structure

```text
1st_mlflow/
│
├── 1st_mlflow.ipynb
│
└── screenshots/
    ├── Dashboard.png
    ├── Metrics.png
    └── Parameters.png
```

---

## 📊 Dataset

The dataset is generated using Scikit-Learn's `make_classification()` function.

### Configuration

| Parameter | Value |
|------------|--------|
| Samples | 1000 |
| Features | 10 |
| Informative Features | 2 |
| Redundant Features | 8 |
| Class Distribution | 90% : 10% |
| Random State | 42 |

---

## 🤖 Model

The project uses Logistic Regression with the following configuration:

```python
params = {
    "solver": "lbfgs",
    "max_iter": 1000,
    "multi_class": "auto",
    "random_state": 42
}
```

---

## 📈 Evaluation Metrics

The following metrics are logged to MLflow:

- Accuracy
- Recall (Class 0)
- Recall (Class 1)
- Macro F1 Score

---

## 🔍 MLflow Tracking

MLflow records:

### Parameters

- Solver
- Maximum Iterations
- Multi-class Strategy
- Random State

### Metrics

- Accuracy
- Recall
- F1 Score

### Artifacts

- Trained Logistic Regression Model

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/manasranjanmeher99/1st_mlflow.git
cd 1st_mlflow
```

Install dependencies:

```bash
pip install numpy scikit-learn mlflow jupyter
```

---

## ▶️ Running the Project

### Start MLflow Server

```bash
mlflow server --host 127.0.0.1 --port 5000
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
1st_mlflow.ipynb
```

Run all cells.

---

## 📸 Project Screenshots

### MLflow Dashboard

![Dashboard](1st_mlflow/screenshots/Dashboard.png)

### Logged Parameters

![Parameters](1st_mlflow/screenshots/Parameters.png)

### Logged Metrics

![Metrics](1st_mlflow/screenshots/Metrics.png)
---

## 🎯 Learning Outcomes

This project demonstrates:

- Machine Learning Experiment Tracking
- MLflow Basics
- Model Versioning
- Performance Monitoring
- Reproducible Machine Learning Workflows
- Introduction to MLOps

---

## 🔮 Future Enhancements

- Hyperparameter Tuning
- Cross Validation
- Model Registry
- MLflow Deployment
- Docker Integration
- CI/CD Pipeline

---

## 👨‍💻 Author

**Manas Ranjan Meher**

GitHub: https://github.com/manasranjanmeher99

LinkedIn: https://www.linkedin.com/in/manas-ranjan-meher-606181280/

---

## ⭐ If you found this project useful, please give it a star.
