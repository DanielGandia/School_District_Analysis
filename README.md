# School District Analysis
## Project Overview
The school board has requested to review the data source provided because of some evidence of academic dishonesty and other anomalies. We will use the data provided to produce the following:

1. District Summary
2. School Summary
3. Top 5 and Bottom 5 Performing Schools
4. Math & Reading Scores by Grade
5. Scores by School Spending
6. Scores by School Size
7. Scores by School Type

## Resources
Data Sources: student_complete.csv, schools_complete.csv

Software: Python 3.8.3, Jupyter Notebook 6.1.4, Visual Studio Code 1.54

## Results
### How is the district summary affected?
After the analysis, the district summary was not affected by the anomalies as the scores stayed virtually the same.

### How is the school summary affected?
The overall School Summary doesn't appear to have been affected either. The scores also stayed the same. 

![distrcit_summary.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/district_summary.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

By removing the ninth grade math and reading scores, Thomas High School's performance increase and it made it a top-five scoring school with a high overall score. This shows that there was something wrong with the data regarding the 9th grade scores. 

![top_five_schools.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/top_five_schools.png)

### Below are the results of the ninth-grade scores were affected:

- Math scores by grade

![math_reading_scores.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/math_reading_scores.png)

- Reading scores by grade

![reading_scores_new.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/reading_scores_new.png)

- School Spending

![score_by_spend.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/score_by_spend.png)

- School Size

![scores_by_size.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/scores_by_size.png)

- School Type

![scores_by_type.png](https://github.com/DanielGandia/School_District_Analysis/blob/main/Resources/scores_by_type.png)

## Summary
The four major changes in the analysis are:

1. The 9th grade data for Thomas High School had anomolies that were not fully identified but it affected the results. 

2. Schools with lower funding had better overall scores than schools with higer funding and spend per student. 

3. Charter schools had better scores in every category than Disctrict schools. 

4. Schools that are Small and Medium size have a higher overall passing percentage than Large school size. 
