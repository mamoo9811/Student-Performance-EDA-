# Student Performance EDA

## 1. Project Overview

This project analyzes student exam performance using Python and data analysis tools. It explores student scores in Math, Reading, and Writing to understand the factors related to academic performance.

## 2. Business Problem and Objective

Schools need to understand student performance and identify factors related to exam results.

The main objective is to analyze student scores and provide useful information to help teachers and school administrators improve student support.

## 3. Dataset Summary

The dataset contains 1,000 student records and 8 original columns.

It includes:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## 4. Methodology

The project was completed through the following steps:

1. Data inspection and understanding.
2. Data cleaning and quality checks.
3. Data preparation and creation of new features.
4. Statistical analysis of Math Scores.
5. Univariate analysis.
6. Multivariate analysis.
7. Conclusions and recommendations.

### Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab
- GitHub

## 5. Key Findings

### 5.1 Math Score Distribution

The histogram shows the distribution of students' Math Scores. Most students scored between 50 and 80, with the highest number of students scoring around 65–70.

The distribution appears approximately bell-shaped, with a slight negative skew. However, the normality test showed a p-value below 0.05, indicating that the scores are not normally distributed statistically.

![Math Score Distribution](images/math_distribution.png)

### 5.2 Correlation Between Exam Scores

The correlation heatmap shows positive relationships between the three subjects.

The strongest relationship is between Reading and Writing, with a correlation coefficient of 0.95. Math also shows strong positive relationships with Reading (0.82) and Writing (0.80).

This means that students who achieve higher scores in one subject tend to achieve higher scores in the other subjects.

![Correlation Between Exam Scores](images/insight_1.png)

### 5.3 Math Scores by Parental Education

The boxplot compares Math Scores across different parental education levels.

It shows differences in median scores and score distributions between the groups. Students whose parents have a Master's degree appear to have a higher median Math Score, while some other education groups show lower median scores.

This suggests that parental education may be related to students' academic performance.

![Math Scores by Parental Education](images/insight_2.png)

## 6. Recommendations

Based on the analysis, the following recommendations are suggested:

- Provide test preparation courses for students.
- Offer additional support for students with low scores.
- Encourage students to improve their reading and writing skills.
- Promote parental involvement in students' education.
- Provide equal learning opportunities for all students.
- Monitor student performance regularly.

## 7. Limitations

- The dataset contains only 1,000 student records.
- Important factors such as study time and attendance are not included.
- The analysis identifies relationships but does not prove cause and effect.
- The dataset may not represent all schools or student populations.

## 8. Next Steps

Future work could include:

- Analyzing data from more students and schools.
- Exploring additional factors related to academic performance.
- Comparing student performance across different schools.
- Developing student support programs based on the analysis results.

## 9. Technical Notebook

The complete analysis, including Python code, data preparation, visualizations, and statistical results, is available in the notebook below.

[Student Performance EDA Notebook](Student_Performance_EDA.ipynb)
