# 📊 Cement Slump Strength Prediction (Regression Analysis)

This project is a complete regression analysis on a real-world dataset to **predict the compressive strength of cement** using various linear models, including regularized techniques like Ridge, Lasso, and ElasticNet.

---

## 👩‍💻 Author

**Your Name**  
Computer Science Student & Aspiring Data Analyst 💻📈  

---

## 📝 Problem Statement

Given a dataset containing the proportions of cement ingredients and slump values, the goal is to build regression models that can predict:

**➡️ Compressive Strength (28-day)(Mpa)**

---

## 🧰 Tools and Libraries Used

- `Python 3.x`
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `scikit-learn`
- `statsmodels`

---

## 🔍 Project Workflow

1. **EDA (Exploratory Data Analysis)**
   - `.describe()`, `.info()`, `.corr()`
   - Visualizations (heatmap, pairplot, boxplot)

2. **Multicollinearity Check**
   - Variance Inflation Factor (VIF)

3. **Train/Test Split + Scaling**
   - Using `StandardScaler`

4. **Model Building with Pipelines**
   - `LinearRegression`
   - `Ridge`, `RidgeCV`
   - `Lasso`, `LassoCV`
   - `ElasticNet`, `GridSearchCV`

5. **Model Evaluation**
   - `R²`, `MAE`, `MSE`, `RMSE`, `MAPE`
   - Comparison table

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- `R² Score`
- `Mean Absolute Error (MAE)`
- `Mean Squared Error (MSE)`
- `Root Mean Squared Error (RMSE)`
- `Mean Absolute Percentage Error (MAPE)`

All metrics were computed for both **train** and **test** sets.

---

## 🧪 Model Comparison Results

| Model            | R² (Test) | RMSE (Test) |
|------------------|-----------|-------------|
| Linear           | ✔️        | ✔️          |
| Ridge            | ✔️        | ✔️          |
| RidgeCV          | ✔️        | ✔️          |
| Lasso            | ✔️        | ✔️          |
| LassoCV          | ✔️        | ✔️          |
| ElasticNet       | ✔️        | ✔️          |
| ElasticNet Grid  | ✔️        | ✔️          |

✅ Regularized models improved performance and reduced overfitting.

---

## 📁 Dataset

- File: `cement_slump.csv`
- Target: `Compressive Strength (28-day)(Mpa)`
- Features: Cement, Slag, Water, SP, Coarse Aggr., Fine Aggr., Flow, Slump

---

## 💬 Final Thoughts

This project is part of my machine learning learning path.  
It shows how to handle **linear regression modeling**, **regularization**, **cross-validation**, and **hyperparameter tuning** using scikit-learn pipelines.

---

## 🚀 How to Run

1. Clone the repo  
```bash
git clone https://github.com/yourusername/cement-slump-regression.git
cd cement-slump-regression
