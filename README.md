# Student Performance Prediction

## Project Overview
This project focuses on predicting students' academic performance using Machine Learning regression models.

The goal is to predict three student scores:
- Math Score
- Reading Score
- Writing Score

The project explores the dataset, handles missing values, applies preprocessing techniques, and compares multiple regression algorithms to evaluate their predictive performance.

## Dataset
The dataset contains approximately 30,641 student records, with demographic, family, and educational features.

**Target Variables:**
- `MathScore`
- `ReadingScore`
- `WritingScore`

## Project Workflow
1. Data Loading and Inspection
2. Data Cleaning and Handling Missing Values
3. Exploratory Data Analysis (EDA)
4. Feature and Target Selection
5. Train-Test Split
6. Data Preprocessing
7. Model Training and Evaluation
8. 5-Fold Cross-Validation
9. Model Comparison and Ranking

## Machine Learning Models
Six regression models were implemented and compared:

1. Dummy Regressor (Baseline)
2. Linear Regression
3. Ridge Regression
4. Lasso Regression
5. Random Forest Regressor
6. Gradient Boosting Regressor

## Evaluation Metrics
The models were evaluated using:

- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.
- **RMSE (Root Mean Squared Error):** Measures prediction error while penalizing larger errors.
- **R² Score:** Measures how well the model explains the variance in the target variable.

5-Fold Cross-Validation was also used to assess model performance stability.

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure
```text
Student_Performance_Prediction/
│
├── Student_Performance_Prediction.ipynb
├── Expanded_data_with_more_features.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/ebrahim-magdy/student-performance-prediction.git
```

2. Navigate to the project directory:
```bash
cd student-performance-prediction
```

3. Install the required libraries:
```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:
```bash
jupyter notebook
```

5. Run `Student_Performance_Prediction.ipynb`.

## Project Goal
The main objective is to compare different regression algorithms, understand their performance, and identify which models provide the best predictions for each student score.

---

**Author:** Ebrahim Magdy  
**GitHub:** [ebrahim-magdy](https://github.com/ebrahim-magdy)  
**LinkedIn:** [Ebrahim Magdy](https://www.linkedin.com/in/ebrahim-magdy/)
