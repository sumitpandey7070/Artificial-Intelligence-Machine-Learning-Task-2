# 🤖 AI & Machine Learning – Task 2
### Feature Engineering, Model Optimization & Performance Comparison
**Maincrafts Technology Internship**

---

## 📌 Objective

This project builds an **enhanced House Price Prediction system** that demonstrates real-world ML workflows including feature scaling, multi-model training, and structured performance comparison.

## 🏗️ What's Built

| Component | Description |
|-----------|-------------|
| Feature Scaling | StandardScaler applied to all input features |
| Multiple Models | Linear Regression, Ridge Regression, Decision Tree |
| Model Comparison | RMSE and R² metrics compared across all models |
| Visualizations | Correlation heatmap, bar charts, Actual vs Predicted plots |
| Model Export | Best model saved using `joblib` |

---

## 📂 Repository Structure

```
AI_ML_Task2/
│
├── AI_ML_Task2_Model_Comparison.ipynb   # Main Jupyter Notebook
├── requirements.txt                      # Python dependencies
├── README.md                             # This file
├── best_model.pkl                        # Saved best model (generated on run)
└── scaler.pkl                            # Saved scaler (generated on run)
```

---

## 📊 Dataset

**California Housing Dataset** (built into scikit-learn)

- **Target:** Median House Value (`HousePrice`)
- **Features:** MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude

---

## 🔧 Models Trained

| Model | Purpose |
|-------|---------|
| Linear Regression | Baseline |
| Ridge Regression | Reduces overfitting (L2 regularization) |
| Decision Tree Regressor | Captures non-linear relationships |

---

## 📈 Evaluation Metrics

- **RMSE** – Root Mean Squared Error (lower = better)
- **R² Score** – Coefficient of Determination (higher = better, max 1.0)

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/AI_ML_Task2.git
cd AI_ML_Task2
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook AI_ML_Task2_Model_Comparison.ipynb
```

### 4. Run all cells
Go to **Kernel → Restart & Run All**

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
notebook
```

---

## 🧠 Key Concepts Covered

- Feature Scaling (StandardScaler)
- Train-Test Split
- Multi-model training and comparison
- Overfitting awareness (Ridge vs Linear)
- Evaluation metrics (RMSE, R²)
- Model persistence with joblib

---

## ✅ Deliverables

- [x] Jupyter Notebook (`AI_ML_Task2_Model_Comparison.ipynb`)
- [x] Model performance comparison table
- [x] Best model saved with `joblib`
- [x] Visualizations (heatmap, bar charts, scatter plots)

---

*Submitted as part of the Maincrafts Technology AI/ML Internship – Task 2*
