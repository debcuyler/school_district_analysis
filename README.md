# School District Analysis

## Overview
Maria has asked me to help her analyze, clean and group student and school data for a district summary report out. She needs a snapshot of the district's key metrics, an overview of metrics for each school and a table that presents the top and bottom five schools, the average math and reading scores by grade level, school performance based on budget per student, school size and school type. She also believes that there has been some academic dishonesty and would like the entire analysis completed a second time after excluding the math and reading scores for all 9th graders at Thomas High School and to compare with the original analysis
## Results
- How is the district summary affected? The district summary report was virtually unchanged by removing the Thomas High School math and reading scores for the 9th grade. As you can see in between the two images below, there is very little change before and after removing the scores

- How is the school summary affected? The school summary is unchanged for all schools except for Thomas High School. When including the 9th grade students in the summary, the percentage passing dropped significantly for Thomas High School for Math, Reading and Overall passing. This is due to including the number of 9th graders in the percentage but without having any scores. Once the Thomas High School percentages were refactored to include only 10th thru 12th grade, the percentages were mostly unchanged from when the 9th grade scores were included in the original analysis.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? When we changed the 9th grade students scores to NaN(not a number), Thomas High School ranking went from being a top 5 school to being closer to a bottom performing school. Once the scores were refactored completely without the 9th grade scores, they are included in the top 5 schools again.
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade: There was no effect on the math and reading scores by grade since each grade is contained within own scoreing. Thomas High School was 
      unable to report scores for the 9th grade.
    - Scores by school spending: Since the 9th grade scores were completely removed and the overall passing percentage was replaced with only the 10th - 12th grade scores, there         was no change in the scores by school spending
    - Scores by school size: Since the 9th grade scores were completely removed and the overall passing percentage was replaced with only the 10th - 12th grade scores, there             was no change in the scores by school size
    - Scores by school type: Since the 9th grade scores were completely removed and the overall passing percentage was replaced with only the 10th - 12th grade scores, there             was no change in the scores by school type

## Summary
- The four major scores that have changed after changing the 9th grade scores to NaN were the Thomas High School % Passing Math, % Passing Reading and % Overall Passing. It also dropped their ranking out of the top 5 performing schools. Using NaN to remove the scores, but keep the numbers of students the same gives a totally different picture of the school performance than it does if you merely remove the scores and student count from the calculations.
