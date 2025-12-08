# Python_Analysis_DataScienceStudentMarks

📌 Project Overview

This project explores a dataset of student exam scores across multiple global locations to analyze technical skill performance, identify statistical patterns, and build a simple predictive model using Python. The analysis uses Pandas, NumPy, and Statsmodels to answer structured analytical questions and develop meaningful insights.

<br>
📂 Dataset Description

Each row represents a student and contains the following fields:

student_id

location

age

sql_marks

excel_marks

python_marks

power_bi_marks

english_marks

This dataset, while small, is well-suited for practicing data exploration, descriptive statistics, and introductory modeling.

<br>
🐍 Python Analysis

Python was used to answer several core analytical questions:

1. What is the average, median, minimum, and maximum score for each subject?

Used Pandas and NumPy descriptive statistics.

2. Which location has the highest average technical skill score?

Created a tech_avg feature and identified the highest-scoring location.

3. What percentage of students scored above 90 in each subject?

Used Boolean filtering and NumPy summation.

4. Which student has the most balanced skillset (lowest variance)?

Computed student-level variance across all subjects using np.var().

5. What is the correlation between all skill scores?

Generated a correlation matrix using df.corr().

6. What is the average age of students scoring above the mean in Python?

Filtered rows by condition and computed their mean age.

7. Which location has the highest variance in skill scores across subjects?

Used groupby(location).var() and aggregated variance to compare variability by city.

8. Can we predict English marks using technical skill scores and age?

Built a linear regression model using Statsmodels:

Selected numeric predictors

Added an intercept

Fit the OLS model

Examined coefficients, p-values, R², and model diagnostics

<br>
🧠 Skills Demonstrated

Exploratory Data Analysis (EDA)

Feature engineering (averages, variances, correlations)

Vectorized data operations with Pandas and NumPy

Linear regression modeling using Statsmodels

Statistical interpretation (variance, correlations, significance)

Clean, reproducible analysis workflow

<br>
📈 Key Findings

Skill scores display meaningful correlations, with certain technical subjects trending together.

Some locations show higher overall variance in performance, indicating greater skill diversity.

The regression model reveals which technical subjects most strongly relate to English performance.

A subset of students demonstrates notably balanced or unbalanced skill profiles.

<br>
🚀 Future Improvements

Add data visualizations using Matplotlib or Seaborn

Build a predictive pipeline with train/test splits

Explore classification (e.g., high vs. low performers)

Add clustering (e.g., K-Means) to identify student skill profiles

Expand dataset or simulate additional samples for more robust modeling

<br>
[Data Science Student Marks Dashboard](https://public.tableau.com/app/profile/audrey4991/viz/DataScienceStudentMarks/StudentMarksStoryBoard) <br>
[Data Science Student Marks Dashboard](https://public.tableau.com/app/profile/audrey4991/viz/DataScienceStudentMarks/StudentMarksStoryBoard)

A dashboard showing how student skill performance (in SQL, Excel, Python, Power BI) varies across locations and age — highlighting overall trends, correlations between skills, and relative strengths or weaknesses for students 
