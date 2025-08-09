# Email-Spam-Detection-Using-a-Hybrid-Model

## 📊 1. Data Preprocessing

- Loaded dataset using `pandas`
- Handled missing values, outliers, and categorical encoding
- Applied normalization and scaling
- **Visualization:**
  - Distribution plots
  - Correlation heatmaps
  - Class imbalance charts


## 🧬 2. Feature Engineering

- Created new features based on domain logic
- Applied dimensionality reduction (e.g., PCA)
- **Visualization:**
  - PCA variance ratio
  - Feature importance plots
  - Scatter plots of principal components

---

## 🤖 3. Model Training & Evaluation

We trained and evaluated five classification models using a consistent train-test split strategy:

```python
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)


✅ Models Used
Logistic Regression

Random Forest

XGBoost

<img width="1090" height="444" alt="image" src="https://github.com/user-attachments/assets/32a9979a-5552-4710-957f-ee7e09f9f4e8" />

🔀 4. Ensemble Learning
-Combined top-performing models using VotingClassifier
-Improved robustness and generalization
-Final ensemble used for prediction and interpretation

🔍 5. Explainable AI with LIME
To interpret and explain individual predictions, we integrated LIME (Local Interpretable Model-Agnostic Explanations).


