#  Diabetes Disease Prediction

A Machine Learning project that predicts whether a patient has diabetes or not using the Pima Indians Diabetes Dataset.

##  Dataset
- **Source:** Kaggle — Pima Indians Diabetes Database
- **Samples:** 768 patients
- **Features:** 8 (Glucose, BMI, Age, Insulin, etc.)
- **Target:** 0 = No Diabetes, 1 = Diabetes

##  Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

##  Project Structure
- `diabetes.csv` — Original dataset
- `diabetes_cleaned.csv` — Cleaned dataset
- `diabetes_prediction.ipynb` — Main notebook

##  Project Workflow
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing (Missing values, Scaling)
3. Model Building (3 Models)
4. Model Evaluation (Accuracy, AUC, Confusion Matrix)
5. Feature Importance Analysis

##  Model Performance

| Model | Accuracy | AUC |
|---|---|---|
| Logistic Regression | 70.78% | 0.81 |
| **Random Forest** | **76.00%** | **0.82** |
| XGBoost | 75.97% | 0.81 |

##  Best Model
**Random Forest** — Accuracy: 76% | AUC: 0.82

##  Top 3 Important Features
1. **Glucose** (0.28) — Most important feature
2. **BMI** (0.16)
3. **DiabetesPedigreeFunction** (0.13)

##  Conclusion
- Glucose is the strongest predictor of diabetes
- Random Forest outperformed all other models
- AUC of 0.82 shows model is significantly better than random guess

##  Author
**Waleed Ahmad**
BSDS Student(2nd Semester) — Riphah International University Faisalabad
[GitHub](https://github.com/mianwaleed155847-hub)
