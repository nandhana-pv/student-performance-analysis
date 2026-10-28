# Student Performance Data Analysis

Exploratory data analysis of the Kaggle "Students Performance in Exams" dataset (spscientist), with 1,000 records.

## What I did
- Cleaned the data: standardized column names, checked for missing values and duplicates (none found), and corrected data types
- Compared math, reading, and writing scores by test preparation, lunch type, parental education, and gender
- Created 3 visualizations using Matplotlib

## Tools
Python, Pandas, Matplotlib, Google Colab

## Key Findings
- **Overall averages:** math 66.09, reading 69.17, writing 68.05
- **Test preparation:** Students who completed the course scored higher in all three subjects. Averages were 69.70 vs 64.08 in math, 73.89 vs 66.53 in reading, and 74.42 vs 64.50 in writing (gap of about 5.6, 7.4, and 9.9 points).
- **Lunch type:** Students with a standard lunch scored higher than those with free/reduced lunch. The gap was about 11.1 points in math, 7.0 in reading, and 7.8 in writing.
- **Parental education:** Scores generally rise with parental education. The high school group had the lowest averages (62.14 math, 64.70 reading, 62.45 writing) and the master's degree group the highest (69.75 math, 75.37 reading, 75.68 writing).
- **Gender:** Male students scored about 5.1 points higher in math (68.73 vs 63.63). Female students scored about 7.1 points higher in reading (72.61 vs 65.47) and 9.2 points higher in writing (72.47 vs 63.31).

Note: results describe this dataset only and do not show cause and effect.

## Files
- `student_performance_analysis.ipynb`: full analysis
- `StudentsPerformance.csv`: dataset
- `chart1_score_distribution.png`, `chart2_test_prep.png`, `chart3_parental_education.png`: charts

## Dataset
Kaggle: Students Performance in Exams (spscientist)