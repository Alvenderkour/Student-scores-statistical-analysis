# Student Scores: Statistical Analysis

## Project Overview

This project analyzes student performance in Mathematics and Language using Python. It investigates gender differences in scores and examines whether parental education level is associated with differences in academic performance.

## Objectives

- Explore and understand the student scores dataset.
- Clean and prepare the data for analysis.
- Perform exploratory data analysis (EDA).
- Compare Mathematics and Language scores between male and female students.
- Investigate score differences across parental education levels.
- Identify significant group differences using post-hoc comparisons.

## Dataset Description

The dataset contains student information and academic scores.

Main variables:

- student ID: Identifier for each student.
- gender: Student gender.
- parental level of education: Education level of the student's parents.
- subject: Academic subject (Mathematics or Language).
- score: Student's score.

## Project Structure

- 01_data_preprocessing.ipynb — Data inspection, cleaning, and preparation.
- 02_statistical_analysis.ipynb — Exploratory analysis, visualizations, hypothesis testing, and findings.
- Scores_cleaned.csv — Cleaned dataset used for statistical analysis.

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- JupyterLab

## Methodology

1. Data inspection and preprocessing.
2. Descriptive statistics and exploratory data analysis.
3. Welch's independent-samples t-tests to examine gender differences.
4. One-way ANOVA to examine differences across parental education groups.
5. Tukey's HSD post-hoc comparisons to identify specific group differences.

## Key Findings

- Female students achieved a higher average Language score than male students.
- Male students achieved a higher average Mathematics score than female students.
- ANOVA indicated statistically significant differences in both Mathematics and Language scores across parental education groups.
- Tukey's HSD identified specific parental education groups with statistically significant differences.

## Conclusion

The analysis identified gender differences in average scores and differences across parental education groups. These results describe patterns and associations in the dataset; they do not establish that parental education causes differences in academic performance.

## How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries.
3. Run 01_data_preprocessing.ipynb.
4. Run 02_statistical_analysis.ipynb.

Ensure that Scores_cleaned.csv is available in the location expected by the second notebook.

## Author

Alvender kour