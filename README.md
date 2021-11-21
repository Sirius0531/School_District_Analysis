# School_District_Analysis

## Overview of the school district analysis: 
The project is to analyze the data of the entire school district. For example, the relationship between budget, school size, school type, and grades. To understand insights and intuitively provide clear results of each school’s performance. In addition, to maintain the test standards, because a group of students is of a certain grade, two analyses were conducted. The impact of specific data on the overall data is also discussed.

## Results:


###### How is the district summary affected?How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The original average reading and math grades are:
![original](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/old_average.PNG)
and after replace the 9th grade at Thomas High School with Nan (461 records), the new average score are:

![new](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/new_average.PNG)
When reassessing the average scores and pass rates of the district’s 15 high schools, the average math score fell by 0.1 and the average reading score fell by 0.02 (almost the same). And the overall pass rate dropped by 1%.
###### How is the school summary affected?
The original school summary:
![original](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/scool_summary_no9th.PNG)
-The overall passing percentage for Thomas High School fell to 65%
-The overall passing percentage for the entire district fell to 64.9%
and after took of the 9th grade at Thomas High School with Nan, the new school summary:
![new](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/scool_summary_9th.PNG)
- Overall passing rate of 90.63% among their tenth through twelfth graders.
- The overall passing percentages of Thomas High School decreased by 0.11%
- The average scores of Thomas High School for math and reading increased by 0.06
######Top 5 performance school:
![new](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/top%205.PNG)
######Low 5 performance school:
![new](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/low%205.PNG)
###### Math and reading scores by grade
![original](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/score_by_grade.PNG)
###### Scores by school budget spending
![original](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/grade_by_budget.PNG)
- The more budget spent per student, the lower overall passing % the school have
###### Scores by school size
![original](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/grade_by_size.PNG)
- Small and mdeium size schools have similar level of performance, however, the larger size of the schools have lower passing %.
###### Scores by school type
![original](https://github.com/Sirius0531/School_District_Analysis/blob/main/Resources/grade_by_type.PNG)
- Charter schools have higher passing % than District schools.
###### Summary:
 The exchange of NaN for grade ninth grades resulted in the overall passing rate of Thomas High School. The average score also dropped. Average math and reading scores across the school district and the overall pass rate of students also declined. Therefore, the scores of the ninth-grade students have a certain degree of influence on the overall performance. However, the total number of students was updated to exclude students in grades 10-12 of Thomas High School and regained a higher average score from the data set.
