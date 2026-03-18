# 🩺 Diabetes Analysis: Exploratory Data Analysis & Machine Learning Pipeline

This project explores a diabetes dataset using **Python**, performing both **Exploratory Data Analysis (EDA)** and a **Machine Learning classification pipeline** to predict diabetes outcomes.  
It blends technical rigor with clear communication—ideal for showcasing data analysis, preprocessing, visualization, and model‑building skills.

---

## 📂 Project Structure

Diabetes_analysis/
│
├── data/
│   └── diabetes.csv
│
├── src/
│   ├── eda.py
│   └── model.py
│
├── README.md
├── LICENSE
└── .gitignore


---

## 🔍 1. Exploratory Data Analysis (EDA)

The EDA script (`src/eda.py`) performs:

### ✔ Data Cleaning
- Replaces biologically impossible zeros with `NaN`
- Fills missing values using column means
- Ensures dataset consistency for modeling

### ✔ Visualizations
- **Gender distribution**
- **Correlation heatmap**
- **Glucose distribution**

These plots help reveal:
- Class imbalance  
- Feature relationships  
- Potential predictors for diabetes outcome  

Run EDA:

```bash
python src/model.py

Model Performance
The model outputs:

Accuracy score

Precision, Recall, F1-score

Confusion matrix visualization

This provides a clear understanding of how well the model predicts diabetes outcomes.

🛠 Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit‑learn

🚀 Future Improvements
Add hyperparameter tuning (GridSearchCV)

Try alternative models (Random Forest, XGBoost)

Build a Streamlit dashboard

Deploy model via API or cloud service

📄 License
This project is licensed under the MIT License.

✨ Author
Toba  
Data & Communications Specialist
Focused on analytics, storytelling, and building tools that support public‑sector and community impact.
