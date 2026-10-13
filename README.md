# Student Performance Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a student performance dataset containing 649 student records and 33 features. The goal is to understand patterns in students' academic performance and explore how study time, absences, previous failures, and other factors relate to final grades.

## Objectives
- Understand the dataset using descriptive statistics.
- Check for missing values and duplicate records.
- Analyze the distribution of students' final grades.
- Explore the relationship between study time and final grades.
- Compare average final grades by gender and school.
- Examine correlations between numerical features and final grades.

## Dataset Information
- **Total records:** 649
- **Total columns:** 33
- **Target column for analysis:** `G3` (final grade)
- **Grade columns:** `G1`, `G2`, and `G3`

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed
1. Dataset overview and data types.
2. Missing-value and duplicate checks.
3. Descriptive statistical analysis.
4. Average grade comparison across G1, G2, and G3.
5. Study time vs. final grade visualization.
6. Absences vs. average final grade visualization.
7. Correlation analysis and heatmap.
8. Gender-wise average grade comparison.
9. School-wise average grade comparison.
10. Final grade distribution visualization.

## Key Findings
- The dataset contains no missing values or duplicate rows.
- Average grades increase slightly from G1 to G2 and G3.
- G2 has a strong positive correlation with G3 (approximately 0.919).
- G1 has a strong positive correlation with G3 (approximately 0.826).
- Study time has a weak positive correlation with G3 (approximately 0.250).
- Previous failures have a negative correlation with G3 (approximately -0.393).
- Absences have a very weak negative correlation with G3 (approximately -0.091).

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install pandas matplotlib seaborn jupyter`
3. Open the project notebook in Jupyter Notebook.
4. Run the notebook cells in order.

## Conclusion
This project demonstrates how EDA and data visualization can be used to identify patterns in student performance. Previous grades show stronger correlations with final grades than study time or absences in this dataset. Correlation does not imply causation, and the findings should not be generalized beyond the analyzed data.

## Author
Rajkumar Pandit
