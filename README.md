# 🏠 California Housing Price Prediction using Random Forest and MLflow

This project demonstrates a complete machine learning pipeline in a **Jupyter Notebook**, using the **California Housing dataset** to predict median house prices. It includes hyperparameter tuning with `GridSearchCV` and experiment tracking with `MLflow`.

---

## 🚀 Features

- ✅ California Housing Dataset (via `sklearn.datasets`)
- ✅ Random Forest Regressor model
- ✅ Hyperparameter tuning using `GridSearchCV`
- ✅ Model evaluation (Mean Squared Error)
- ✅ MLflow tracking and model logging

---

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- scikit-learn
- mlflow
- pandas & numpy

---
<img width="957" alt="image" src="https://github.com/user-attachments/assets/70a8f439-a487-4d21-bb87-cbfdc7b3a9a5" />


<img width="155" alt="image" src="https://github.com/user-attachments/assets/86fa033f-a01b-4864-8a31-d8cbb76943ea" />


## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/housing-price-mlflow.git
   cd housing-price-mlflow
    ```

2. **Create and activate a virtual environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. **Install the dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Start the MLflow UI**
    ```bash
    mlflow ui
    ```
    Open your browser and go to http://127.0.0.1:5000

5. **Run the notebook cell-by-cell to:**
    - Load dataset
    - Train and tune the model
    - Log metrics and model to MLflow


### Example Logged Data in MLflow UI

- Parameters: n_estimators, max_depth, min_samples_split, min_samples_leaf
- Metric: Mean Squared Error (MSE)
- Model: Tracked and optionally registered
    
## 📁 File Overview
    ```bash
    california_housing_rf.ipynb   # Your main Jupyter notebook
    README.md                     # This file
    ```


# 🧠 Notes
- Data used: fetch_california_housing() from sklearn.datasets
- RandomForestRegressor was used due to its robustness and suitability for tabular regression
- GridSearchCV finds the best set of hyperparameters
- MLflow tracks experiments and stores model artifacts
