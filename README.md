# Students Performance Analysis 📊

## Project Overview

This project analyzes the academic performance of 1,000 students across Mathematics, Reading, and Writing.

The goal is to explore patterns in student performance and investigate how different factors are associated with academic outcomes.

## Objectives

- Analyze students' performance across different demographic groups.
- Investigate the relationship between test preparation and exam scores.
- Explore the relationship between parental education and student performance.
- Analyze performance differences by lunch type and race/ethnicity.
- Examine correlations between Mathematics, Reading, and Writing scores.
- Identify key insights from the dataset.

## Dataset

The dataset contains 1,000 student records and 8 original variables:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Key Results

- Average Math Score: **66.09**
- Average Reading Score: **69.17**
- Average Writing Score: **68.05**
- Overall Average Score: **67.77**
- Test Preparation Completion Rate: **35.80%**

Students who completed the test preparation course achieved higher average scores across all three subjects.

The largest improvement was observed in Writing, with approximately **15.37%** higher average performance compared with students who did not complete the course.

Reading and Writing also showed a very strong positive correlation of approximately **0.95**.

## Data Analysis Process

### 1. Data Inspection
- Dataset dimensions
- Data types
- Descriptive statistics
- Missing value checks

### 2. Data Cleaning
- Duplicate detection
- Missing value detection
- Invalid score detection
- Categorical variable encoding

### 3. Exploratory Data Analysis
- Score distributions
- Gender performance
- Test preparation impact
- Parental education
- Lunch type
- Race/Ethnicity
- Overall student performance
- Top and bottom performers
- Correlation analysis

### 4. Visualization

The project uses:

- Matplotlib
- Seaborn

to create charts and identify patterns in the data.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Files

- `Students_Performance_Analysis.ipynb` — Main analysis notebook
- `README.md` — Project documentation

## Conclusion

The analysis demonstrates how Python-based data analysis can be used to explore educational data, identify meaningful patterns, and generate data-driven insights.

The findings describe associations within the dataset and should not be interpreted as proof of causal relationships.
