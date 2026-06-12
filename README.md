# Student Academic Performance Analysis

## Project Overview

This project investigates the influence of gender and parental educational attainment on student academic performance in Mathematics and Language subjects using statistical hypothesis testing techniques.

The analysis was conducted as a reproducible Python-based statistical study, following a structured research workflow including data exploration, hypothesis formulation, inferential statistics, effect size analysis, and result interpretation.

---

## Research Objective

The primary objective of this study is to examine whether demographic and family-background factors significantly affect academic achievement.

Specifically, the study evaluates:

- The impact of gender on Mathematics performance.
- The impact of gender on Language performance.
- The impact of parental educational attainment on Mathematics performance.
- The impact of parental educational attainment on Language performance.

---

## Research Questions and Hypotheses

### RQ1
Does gender significantly influence Mathematics performance?

**H₀:** There is no significant difference in Mathematics scores between male and female students.

**H₁:** There is a significant difference in Mathematics scores between male and female students.

---

### RQ2
Does gender significantly influence Language performance?

**H₀:** There is no significant difference in Language scores between male and female students.

**H₁:** There is a significant difference in Language scores between male and female students.

---

### RQ3
Does parental educational attainment significantly influence Mathematics performance?

**H₀:** Mean Mathematics scores are equal across all parental education groups.

**H₁:** At least one parental education group has a different mean Mathematics score.

---

### RQ4
Does parental educational attainment significantly influence Language performance?

**H₀:** Mean Language scores are equal across all parental education groups.

**H₁:** At least one parental education group has a different mean Language score.

---

## Dataset Description

The dataset contains student performance records with the following variables:

| Variable | Description |
|-----------|------------|
| student_id | Unique student identifier |
| gender | Student gender |
| parental.level.of.education | Highest parental educational attainment |
| subject | Academic subject (Mathematics or Language) |
| score | Examination score |

### Dataset Summary

- Total Records: 972
- Numerical Variables: 1
- Categorical Variables: 4
- Missing Values: None

---

## Statistical Methods

The following statistical techniques were applied:

### Independent Samples t-Test
Used to compare mean scores between male and female students.

### Cohen's d Effect Size
Used to measure the practical significance of gender differences.

### One-Way ANOVA
Used to determine whether mean scores differ across parental education groups.

### Tukey's HSD Post-hoc Test
Used to identify specific group differences when ANOVA results were significant.

---

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
Student-Academic-Performance-Analysis/
│
├── input_data/
│   └── Scores.csv
│
├── notebooks/
│   └── TU_Dortmund_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Reproducibility

### Clone Repository

```bash
git clone https://github.com/Shrutibeladia/Student-Academic-Performance-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/TU_Dortmund_Analysis.ipynb
```

---

## Key Findings

The statistical analysis investigates whether demographic and family-background factors significantly influence student performance.

The findings include:

- Gender-based comparison of Mathematics scores.
- Gender-based comparison of Language scores.
- Influence of parental educational attainment on Mathematics performance.
- Influence of parental educational attainment on Language performance.
- Effect size estimation and post-hoc group comparisons.

Detailed results and interpretations are available in the Jupyter notebook.

---

## Academic Relevance

This project demonstrates practical application of:

- Statistical Inference
- Hypothesis Testing
- Effect Size Analysis
- Exploratory Data Analysis
- Research-Oriented Data Science
- Reproducible Scientific Computing

The project reflects skills commonly required in Data Science and Statistical Learning programs.

---

## Author

**Shruti Beladia**

Data Scientist | Software Engineer | Data Analytics 

GitHub: https://github.com/Shrutibeladia
