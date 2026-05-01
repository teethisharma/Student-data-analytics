# Student Exam Scores Analytics 🎓

##  Executive Summary
This project analyzes a comprehensive dataset of student exam scores to identify the socio-economic and behavioral drivers of academic success. By examining Math, Reading, and Writing performance, the analysis uncovers how factors like parental education, gender demographics, and study habits correlate with student outcomes. The goal is to provide data-driven insights that can help educators identify at-risk students and understand the variables that contribute to high performance.

##  Methodology
1.  **Data Acquisition:** Utilized the `Expanded_data_with_more_features.csv` containing student demographic and performance data.
2.  **Data Cleaning:** 
    *   Removed redundant indexing columns (`Unnamed: 0`).
    *   Inspected dataset for missing values and confirmed data types.
3.  **Exploratory Data Analysis (EDA):** 
    *   Statistical profiling using `describe()` to establish score baselines.
    *   Categorical analysis of gender and ethnic distributions.
4.  **Bivariate Analysis:** Grouped performance data by parental education and study hours to identify trends.
5.  **Visualization:** Employed Heatmaps and Countplots to make statistical correlations easily interpretable.

##  Skills & Tools
*   **Language:** Python
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook / VS Code
*   **Statistical Analysis:** Descriptive Statistics, Correlation Mapping

##  Results
*   **Parental Impact:** There is a significant positive correlation between parental education and student scores. Students whose parents hold a **Master's Degree** consistently outperformed all other groups.
*   **Gender Trends:** The dataset shows a slightly higher enrollment of female students, with specific performance variances noted across different subjects.
*   **Subject Correlation:** A strong positive relationship was found between Reading and Writing scores, suggesting that literacy skills are highly linked.
*   **Study Habits:** Initial findings indicate that students with higher weekly study hours maintain higher average scores in core technical subjects like Math.

##  Next Steps
*   **Predictive Modeling:** Implement a Machine Learning model (e.g., Linear Regression or Random Forest) to predict final scores based on demographic inputs.
*   **Handling Missing Values:** Apply advanced imputation techniques to fill gaps in the `EthnicGroup` and `WklyStudyHours` columns.
*   **Feature Engineering:** Create a "Total Score" column to analyze overall academic standing vs. subject-specific performance.

