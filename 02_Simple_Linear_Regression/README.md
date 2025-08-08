# Project 02 – Simple Linear Regression

This project predicts **placement packages (in LPA)** based on students' **CGPA** using **Simple Linear Regression**.

## 📌 Dataset : placement.csv
- **cgpa** → Student's cumulative grade point average  
- **package** → Placement package offered (in LPA)

Example:
| cgpa | package |
|------|---------|
| 6.89 | 3.26    |
| 5.12 | 1.98    |

## ⚙️ Steps
1. Load dataset using `pandas`
2. Visualize data with `matplotlib`
3. Train `LinearRegression` model from `sklearn`
4. Plot regression line over scatter plot

## 📊 Visualization
Scatter plot with regression line (red) shows the positive correlation between CGPA and package.

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook 02_Simple_Linear_Regression.ipynb
