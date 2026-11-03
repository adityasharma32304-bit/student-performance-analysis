# Student Performance Analysis — Exploratory Data Analysis (EDA)

## Project Overview

This project explores the **Students Performance in Exams** dataset to understand how different factors relate to students' academic performance in mathematics, reading, and writing.

The main goal was to perform Exploratory Data Analysis (EDA), identify patterns in the data, investigate relationships between variables, and draw meaningful insights from the results.

## Dataset

- **Dataset:** Students Performance in Exams
- **Source:** [Kaggle — Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Records:** 1,000 students
- **Features:** 8 columns

### Dataset Features

| Feature | Description |
|---|---|
| gender | Gender of the student |
| race/ethnicity | Student's race/ethnicity group |
| parental level of education | Highest education level of parents |
| lunch | Type of lunch received |
| test preparation course | Whether the student completed test preparation |
| math score | Mathematics exam score |
| reading score | Reading exam score |
| writing score | Writing exam score |

## Objectives

- Understand the structure and characteristics of the dataset.
- Identify missing values and duplicate records.
- Explore score distributions using descriptive statistics.
- Analyze outliers using the Interquartile Range (IQR) method.
- Compare academic performance across different student groups.
- Investigate relationships between lunch type, parental education, test preparation, and exam scores.
- Extract meaningful insights from the data.

## Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib / Seaborn** — Data visualization (where used)

## Analysis Workflow

### 1. Data Understanding
- Loaded and inspected the dataset.
- Examined column names, data types, and dataset dimensions.
- Used descriptive statistics to understand score distributions.

### 2. Data Quality Checks
- Checked for missing values.
- Checked for duplicate records.
- Examined score ranges and data validity.

### 3. Exploratory Data Analysis
- Compared average scores across gender groups.
- Analyzed performance across race/ethnicity groups.
- Investigated the relationship between parental education and student performance.
- Compared scores between students who completed and did not complete test preparation.
- Examined differences between standard and free/reduced lunch groups.

### 4. Outlier Analysis
- Used the IQR method to identify potential outliers.
- Examined outliers across individual subjects.
- Compared outlier patterns within race/ethnicity groups.
- Considered the difference between statistically unusual values and invalid data.

### 5. Cross-Variable Analysis
- Compared parental education distributions across lunch categories.
- Compared test preparation distributions across lunch categories.
- Investigated whether the lunch-score difference persisted within test preparation categories.

## Key Findings

1. Female students had higher average reading and writing scores, while male students had higher average mathematics scores.
2. Group E had the highest average scores across the three subjects, while Group A had the lowest.
3. Higher parental education levels generally corresponded with higher average student scores, although the relationship was not perfectly linear.
4. Students who completed the test preparation course generally achieved higher average scores.
5. Students receiving standard lunch had higher average scores across mathematics, reading, and writing than students receiving free/reduced lunch.
6. The lunch-score difference remained visible even when comparing students within the same test preparation category.
7. The distribution of parental education and test preparation categories was relatively similar across lunch groups, suggesting that differences in these group compositions alone do not explain the observed lunch-score gap.

## Conclusion

This project helped explore how academic performance varies across different demographic and educational factors.

The analysis revealed several patterns, particularly the differences in subject performance across gender groups and the higher average scores associated with test preparation completion and standard lunch.

It also demonstrated how cross-variable analysis can provide a deeper understanding of relationships that may not be obvious from individual comparisons.

**Important:** These findings describe associations in the dataset. They do not establish that any particular factor directly causes higher or lower academic performance.

## Limitations

- The dataset contains only 1,000 student records.
- The analysis identifies associations rather than causal relationships.
- Some potentially relevant factors influencing academic performance may not be included in the dataset.
- Group averages can hide individual differences within each category.

## What I Learned

Through this project, I practiced:

- Exploring datasets using Pandas.
- Performing data-quality checks.
- Using descriptive statistics.
- Applying the IQR method for outlier detection.
- Grouping and comparing data using `groupby()` and `pivot_table()`.
- Performing cross-variable analysis using `crosstab()`.
- Interpreting analytical results and communicating findings.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Status:** EDA Completed  
**Part of:** 30-Day Data Science Mini-Project Challenge