# PyCity Schools Analysis

# Objective
The goal of this project is to aggregate and analyze data from students' standardized test scores to identify trends in school performance. The insights derived will assist the school board and mayor in making informed strategic decisions regarding resource allocation.

# Key Metrics Analyzed
Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% Passing math
% Passing reading
% Overall passing

# Notable Findings
The highest performing school, measured by % overall passing, is Cabrera High School at over 91%, while the lowest performing school is Rodriguez High School at just over 52%.

Passing rates in all subjects tend to decrease as spending increases, and larger schools (2000-5000 students) show lower passing rates compared to smaller (<1000) and medium-sized schools (1000-2000).

Charter schools have higher passing rates compared to district schools.
Data Sources

# Source Data
This analysis utilizes the following data files: schools_complete.csv

# Project Structure
**District Summary:** A high-level snapshot of the district's key metrics.
**School Summary:** Key metrics about each school including demographics and performance.
**Highest/Lowest Performing Schools:** Identification of top and bottom schools by % overall passing.
**Scores by Grade:** Average math and reading scores segmented by grade level.
**Scores by School Spending:** Analysis of school performance based on spending per student.
**Scores by School Size:** Performance metrics categorized by school size.
**Scores by School Type:** Comparison of performance across different school types.

# Additional Resources
For step "Calculate the total budget" I used user @cottontail 's answer of groupby.head(1) from this Stack Overflow question:
https://stackoverflow.com/questions/37105609/drop-duplicates-using-pandas-groupby

For the Highest-Performing School (by % Overall Passing), I referened the pandas documentation on pandas.DataFrame.sort_values https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html

