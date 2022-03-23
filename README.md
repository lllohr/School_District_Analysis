# School_District_Analysis


## Overview of the school district analysis: 

## Purpose of this analysis:

According to the specifications of the project, the previous school analysis needs to be re-run due to suspected cheating on the 9th grade tests of Thomas High School. The school board has sought out the help of Maria and her supervisor to address the suspected academic dishonesty on the state-testing. Maria has asked us to replace the 9th grade Thomas High School scores with NaNs. After the compromised data has been replaced, we were asked to re-run the school analysis and give a report the results.


### Results: 

- How is the district summary affected?

The district summary was impacted in several ways. The first is that the total students changed from 39,170 to 38,709. The average math score changed from 79.0 to 78.9. The passing math percentage changed from 75% to 73.9%. The overall passing reading percentage changed from 85.8% to 84.7%. The overall passing percentage changed from 65.2% to to 64.9% 

Original data:
![District Summary Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/district_summary_original.png)

After dropping the Thomas High School 9th grade scores:
![District Summary Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/district_summary_revised.png)

- How is the school summary affected?

The per school summary is impacted only for the Thomas High School statistics. This impact is minimal, as seen from the following:

![Thomas High School Summary Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/Thomas_High_School_originalpng.png)

![Thomas High School Summary Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/Thomas_High_School_revised.png)

![Per School Summary Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/per_school_summary_df_original.png)

![Per School Summary Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/per_school_summary_df_revised.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

As can be seen from the graphics below, there was no change in Thomas High School's position relative to the other schools. Thomas High School continues to be in the top 5 high schools.

![Top Schools Head Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/top_schools.head_original.png)

![Top Schools Head Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/top_schools.head_revised.png)

- What are some other possible tables and/or graphs that we could create?
We could could possibly create a bar graph that shows the before dropping the ninth grade Thomas High School scores and after. 

### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
![Math Scores by Grade Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/math_scores_by_grade_original.png)

There is no change in the 10-12th grade data.

![Math Scores by Grade Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/math_scores_by_grade_revised.png)

![Reading Scores by Grade Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_original.png)

Reading scores were not impacted by the removal of the 9th grade scores, as the calculations were per grade basis. Eliminating 9th graders did not change the other scores. 

![Reading Scores by Grade Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_revised.png)

- Scores by school spending
![Spending Summary Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/spending_summary_original.png)

There were no changes observed in the data before and after.

![Spending Summary Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/spending_summary_revised.png)

- Scores by school size
![Size Summary Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/size_summary_original.png)

There were no observable changes between the school size summaries before and after dropping the 9th grade scores. 

![Size Summary Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/size_summary_revised.png)

- Scores by school type
![Scores by School Type Original](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/type_summary_original.png)

![Scores by School Type Revised](https://github.com/lllohr/School_District_Analysis/blob/main/Resources/type_summary_revised.png)

### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
-The first is that the total students changed from 39,170 to 38,709.
-The average math score changed from 79.0 to 78.9.
-The overall passing reading percentage changed from 85.8% to 84.7%.
-The overall passing percentage changed from 65.2% to to 64.9% 



