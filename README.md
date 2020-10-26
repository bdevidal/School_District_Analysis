# School_District_Analysis

## Overview:

In this analysis, we have been asked to provide actionable insights for a school district based on a pair of datasets. One is a top level overview of the schools in the city, providing basic information such as type (charter or district), size, and budget. The other is a granular breakdown of individual performance by student, listing that student's name, grade, school, and standardized test score in both reading and math. By applying standard data manipulation and analysis techniques, we were able to combine these data sets to provide various points of comparison (averages broken down by school and grade, spending per student, schools ranked by various performance metrics, etc). This will allow stakeholders to take action based on our best available data.

Once our initial analysis was complete, we were informed that discrepencies had been noticed in one of the data sets. The standardized test scores for one grade at one highschool (9th Grade, Thomas High School) are currently under review due to possible manipulation or academic dishonesty. So as to not overly impair the utility of our analysis, we have decided to go back and remove the questionable data from the dataset and rerun our calculations.

## Results: 

* Overall impact to our district summary results were minimal. Very minor reductions were seen in both average scores and passing percentages, as seen here:

Original District Summary:
![Image](/Resources/Original_District_Summary.png)

Updated District Summary:
![Image](/Resources/Updated_District_Summary.png)



* For the school in question, changes were also minimal. Once those scores were removed and the numbers recalculated, changes were again minor (under 1%), as seen here:

Original School Results:
![Image](/Resources/Original_School_Results.png)

Updated School Results:
![Image](/Resources/Updated_School_Results.png)





* Relative to other schools, Thomas High School did not change rankings.

* Scores by grade were essentially unaffected, since all data issues were contained to a single grade at a single school. This does mean that there is currently no data for the 9th Grade at Thomas High School, pending clarification.

* Scores by school spending were effectively unchanged (only affected the $630 - 644 group, and effect was less than our significant digit rounding).

* Scores by school size were effectively unchanged (only affected the Medium group, and effect was less than our significant digit rounding)

* Scores by school type were effectively unchanged (only affected the Charter group, and effect was less than our significant digit rounding)


## Summary: 

As noted above, while changes could be seen across the data due to the removal of the questionable records, all effects were minor and within minimal margins. 

(Note: Some work completed after deadline)