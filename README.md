# 📊 Student Exam Score Prediction 

This project predicts students' **math scores** based on various features like reading score, writing score, gender, parental education, lunch type, and test preparation course. The dataset used is the publicly available [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) from Kaggle.

## 🚀 Objective

To build a **multiple linear regression model** that accurately predicts math scores and identifies the most influential factors affecting student performance.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn (Linear Regression, Train-Test Split, Evaluation Metrics)
- Matplotlib / Seaborn (Visualizations)
- Google Colab (Development Environment)

---

## 📚 Dataset

- Source: [Kaggle – Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- 1000 records of student scores and demographic attributes

### Features:
- Gender
- Race/Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Reading score
- Writing score

---

## 🔎 Key Steps

1. **Data Cleaning**:
   - Merged similar categories (e.g., `some high school` → `high school`)
   - Handled categorical variables using one-hot encoding

2. **Model Building**:
   - Used `LinearRegression()` from `scikit-learn`
   - Trained the model on 80% of the data, tested on 20%

3. **Evaluation**:
   - R² Score: **0.88**
   - Mean Squared Error (MSE): ~28.67
   - Identified writing score and reading score as the most influential predictors

4. **Interpretation**:
   - Male students and those with standard lunch showed higher predicted scores
   - Surprisingly, students who skipped test prep scored slightly higher (likely due to confounding factors)

---

## 📈 Visualization

- Scatter plot of **Actual vs Predicted** math scores
- Bar chart of feature **coefficients** to interpret impact

---



