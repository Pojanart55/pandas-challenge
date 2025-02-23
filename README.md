# PyCity Schools Analysis

## Overview

This project analyzes standardized test results from a city school district using Pandas and Jupyter Notebook. The goal is to identify trends in school performance to inform strategic decisions regarding school budgets and priorities. The analysis covers district-wide metrics, school-specific metrics, and performance breakdowns based on spending, size, and school type.

## Project Structure
* `README.md`: This file, providing an overview of the project.
* `PyCitySchools.ipynb`: Jupyter Notebook containing the analysis code.
* `schools_complete.csv`: CSV file containing school information.
* `students_complete.csv`: CSV file containing student test scores and demographic information.

## Data Analysis

### 1. District Summary

A high-level snapshot of the district's key metrics was created, including:

* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math
* % passing reading
* % overall passing

### 2. School Summary

Key metrics for each school were calculated and summarized, including:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math
* % passing reading
* % overall passing

### 3. Highest-Performing Schools (by % Overall Passing)

Schools were sorted by `% Overall Passing` in descending order, and the top 5 schools were displayed.

### 4. Lowest-Performing Schools (by % Overall Passing)

Schools were sorted by `% Overall Passing` in ascending order, and the bottom 5 schools were displayed.

### 5. Math Scores by Grade

Average math scores were calculated for each grade level (9th, 10th, 11th, 12th) at each school.

### 6. Reading Scores by Grade

Average reading scores were calculated for each grade level (9th, 10th, 11th, 12th) at each school.

### 7. Scores by School Spending

School performance was analyzed based on average spending ranges per student, using the following spending bins:

* <\$585
* \$585-630
* \$630-645
* \$645-680

### 8. Scores by School Size

School performance was analyzed based on school size, using the following size bins:

* Small (<1000)
* Medium (1000-2000)
* Large (2000-5000)

### 9. Scores by School Type

School performance was analyzed based on school type (Charter or District).

## Observable Trends

Based on the analysis, here are two observable trends:

1.  **Spending vs. Performance:** Schools with higher per-student budgets did not necessarily achieve better test results. In fact, schools with lower spending per student tended to perform better. This suggests that factors other than budget allocation may have a more significant impact on student performance.
2.  **School Size vs. Performance:** Small and medium-sized schools generally outperformed large schools in terms of overall passing rates. This indicates that smaller class sizes or more personalized attention may contribute to better academic outcomes.
