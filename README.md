# Student Performance — EDA + Linear Regression

## Project Description

This project performs Exploratory Data Analysis (EDA) and builds a Linear Regression model on a student academic performance dataset. The objective is to identify factors that influence student performance and predict the Performance Index using machine learning.

Dataset: 10,000 student records | 6 features | No missing values

---

## Key Results

| Metric                    | Value      |
| ------------------------- | ---------- |
| Average Performance Index | 55.2 / 100 |
| Model MAE                 | 1.61       |
| Model RMSE                | 2.02       |
| Error Rate                | ~3.6%      |

---

## Key Findings

### Previous Scores (Correlation: 0.92)

Strongest predictor of performance. Students with strong academic history consistently score higher.

### Hours Studied (Correlation: 0.37)

Moderate positive impact. Consistent study habits improve outcomes.

### Extracurricular Activities

Minimal effect. Only 1 point difference between participants and non-participants.

### Sleep Hours (Correlation: 0.05)

Very weak relationship with performance.

### Sample Papers Practiced (Correlation: 0.04)

Practicing without conceptual understanding has limited impact.

---

## Machine Learning Model

**Algorithm:** Linear Regression

**Target Variable:** Performance Index

**Train/Test Split:** 70% / 30%

**Features:**

* Hours Studied
* Previous Scores
* Extracurricular Activities
* Sleep Hours
* Sample Question Papers Practiced

### Results

* MAE: 1.61
* RMSE: 2.02
* Model predicts with ~96.4% accuracy

---

## Concepts Used

* Exploratory Data Analysis
* Correlation Analysis
* Data Visualization (Histograms, Scatter Plots, Heatmap, Pairplot)
* Feature Encoding
* Train/Test Split
* Linear Regression
* Model Evaluation (MAE, MSE, RMSE)

---

## Project Structure

```text
StudentPerformance/
│
├── StudentPerformance.ipynb
├── StudentPerformance.csv
└── README.md
```

## How to Run

### Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Steps

1. Clone this repository.
2. Place `StudentPerformance.csv` in the project folder.
3. Open `StudentPerformance.ipynb`.
4. Run all cells top to bottom.

---

## Author

Meet Tailor — Data Science Learner

GitHub: https://github.com/MeetTailor-Data

---

## License

Created for learning and educational purposes only.

---

## Status

Completed |  2026
