# 2026-Sprint-Stat-2-Cycle-3

Group 5

# Project Cycle 3

## Group Information

- Group number: 5
- Members: 113370213柯欣妤、112370128陳冠維

## Dataset

- Original dataset: `YRBS_2007.csv`
- Cleaned dataset: `YRBS_2007_cleaned_gender_height.csv`

## Selected Research Question

This project selects **Question 5: Gender and Height**.

Research question:

- Is the mean height different between male and female students?

中文：

- 男性與女性學生的平均身高是否不同？

## Variables

- Group variable: `WhatIsYourSex`
- Response variable: `HowTallAreYouWithoutShoesInMeters`
- Cleaned group variable: `Sex`
- Cleaned response variable: `Height_m`

## Group Definition

This project compares two independent groups:

- Female students
- Male students

## Response Variable

The response variable is height without shoes, measured in meters.

Because height is a quantitative variable, this project compares the mean height between female and male students.

## Statistical Method

The statistical method used in this project is:

- Welch two-sample t-test

Welch two-sample t-test was used because the project compares the mean height of two independent groups and does not assume equal variances.

## Project Workflow

This project was completed in the following steps:

1. Selected the research question
2. Defined the two groups
3. Defined the response variable
4. Cleaned the original dataset
5. Created the cleaned dataset
6. Completed descriptive statistics
7. Completed EDA
8. Completed Welch two-sample t-test
9. Exported notebook files as PDF for easier viewing on GitHub

## Files

### Notebook Files

- `01_data_cleaning_gender_height.ipynb`
- `02_descriptive_statistics_gender_height.ipynb`
- `02b_eda_gender_height.ipynb`
- `03_welch_t_test_gender_height.ipynb`

### PDF Output Files

Because GitHub may not display `.ipynb` files correctly, the notebook files were also exported as PDF files and saved in the `outputs` folder.

- `01_data_cleaning_gender_height.pdf`
- `02_descriptive_statistics_gender_height.pdf`
- `02b_eda_gender_height.pdf`
- `03_welch_t_test_gender_height.pdf`

### Data Files

- `data/data raw/YRBS_2007.csv`
- `data/data processed/YRBS_2007_cleaned_gender_height.csv`

### Output Files

- `outputs/tables/gender_height_descriptive_summary.csv`
- `outputs/tables/gender_height_group_summary.csv`
- `outputs/tables/gender_height_welch_test_results.csv`
- `outputs/figures/mean_height_by_gender.png`
- `outputs/figures/height_boxplot_by_gender.png`
- `outputs/figures/height_histogram_by_gender.png`
- `outputs/figures/gender_height_ci_plot.png`
- `outputs/figures/gender_height_t_distribution_curve.png`
- `outputs/summary/gender_height_welch_interpretation.txt`

## Main Result

The descriptive statistics showed that male students had a higher average height than female students.

The Welch two-sample t-test was used to test whether the mean height difference between male and female students was statistically significant.

At the significance level α = 0.05, the test result showed a statistically significant difference in mean height between male and female students.

## Conclusion

Based on the analysis, male students had a higher average height than female students in the YRBS 2007 dataset.

The result suggests that there is a statistically significant difference in mean height between male and female students.