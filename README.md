# School_District_Analysis
## Overview of the school district analysis
A high-level key performance metrics is provided to school district regarding the performance of high schools under the school District. After the project is submitted, it was revealed that there was academic dishonesty specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.So school District wants to  uphold the test results of Thomas High School ninth grade and re calculate the performance metrics of the school.So project is to update the reading and math grades for  9 th grade at Thomas High School to NaN and apparently performance metric of the school district will be updated.
## Results
Input Data for the analysis at below places

1.SchoolS Data-https://github.com/merinanto/School_District_Analysis/blob/main/Resources/schools_complete.csv

2.Students Data-https://github.com/merinanto/School_District_Analysis/blob/main/Resources/students_complete.csv

Script used to update the metrics is available at https://github.com/merinanto/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb

### Effect on District Summary:-
Math score is affected due to the updation in the student scores.Average math score and math passing percenatge for the district is reduced by 0.1.
Reading score don't have a significant change due to the updation in the student scores.Hence overall pass percentage of the distrcit also reduced by 0.1 on the District Summary.

### Effect on School Summary:-
Average math score & math passing percentage of the school is reduced by 0.15. Average reading score and reading percentage is reduced by 0.1. Overall pass percenatge for the school has reduced by 0.3.

### Relative Performance of Thomas High School:-
Eventhough overall percentage of the school reduced the position as second top performing school for a small margin 0.01. There is large possiblity if actual scores of the 9th grade students updated,school position will be pushed back.

#### Math and reading scores by grade
9th grade score of other schools are uneffected. But overall  average math score went down by 0.1 and average readin score wend down by 0.2.

#### Scores by school spending
Thomas school belongs to bin 630-644 and  student score updation didn't have any significant effect on the scores.
#### Scores by school size
Thomas school has 461 9th graders and evenafter the student score the remains in the bin Medium (1000-2000)	and change didn't make any significant effect on the scores.
#### Scores by school type
Thomas school is charter school and student score updation didn't have any significant effect on the scores.

## Summary
1. Scores for thomas high school 9th graders not considered in performance metrics.
2. Overall pass percenatge and math pass percentage reduced by 0.1 for the district summary report.
3. Overall pass percentage, math pass percentage and reading pass percentage reduced for the school.
4. School is currently maintaing second top position for marginal difference and probably realtive performance of the schoools will change.
