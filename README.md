# Student Marks Prediction – DS Project I

---

## 📁 File Structure

```
student-marks-prediction/
├── DS-A-04-Final.ipynb           # Main Jupyter Notebook
├── preprocessed_dataset.xlsx      # Preprocessed dataset used for model fitting
├── marks_dataset.xlsx            # Original dataset (6 sheets)
└── README.md
```

---

## 📋 Project Overview

A regression-based machine learning project to predict student academic performance using assignment, quiz, and midterm scores.

**Research Questions:**

| RQ | Target | Models Used |
|----|--------|-------------|
| RQ1 | Midterm I marks | Simple, Multiple, Polynomial Regression + Dummy |
| RQ2 | Midterm II marks | Simple, Multiple, Polynomial Regression + Dummy |
| RQ3 | Final Exam marks | Simple, Multiple, Polynomial Regression + Dummy |

**Key steps:**
- EDA with visualizations
- Preprocessing & combining 6 Excel sheets into one dataset
- Regression model training & evaluation (MAE, RMSE, R²)
- Bootstrapping (500 samples) with 95% CI for MAE
- Comparison with baseline DummyRegressor
- Interactive dashboard built with Gradio

---

## 🔧 Libraries Used

- `pandas` / `numpy` – Data manipulation
- `matplotlib` / `seaborn` – Visualization
- `sklearn` – Regression models, metrics, bootstrapping
- `gradio` – Interactive dashboard

---

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/KainatZahraa/student-marks-prediction.git
   cd student-marks-prediction
```

2. Install dependencies:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn gradio
```

3. Launch Jupyter Notebook:
```bash
   jupyter notebook DS-A-04-Final.ipynb
```

> Make sure `marks_dataset.xlsx` and `preprocessed_dataset.xlsx` are in the same directory as the notebook.
