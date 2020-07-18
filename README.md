# School_District_Analysis

## Overview of the school district analysis
The purpose of this exercise was to analyze the performance of students from a variety of schools. After doing an initial analysis, we realized that the  9th grade scores from Thomas High School were untrue and not depicting the actual performance of the students. We therefore eliminated these scores from our overall exercise in order to deliver a more honest and accurate analysis. 

### How is the district summary affected?
As predicted, the eliminatinon of the faulty scores had a negative impact on the overall district's performance. The average math score, average reading score, % of students passing math, % of students passing reading as well as the overall passing rate all decreased after we tweaked the analysis. The resulting scores, even though lower, are a much more accurate representation of the true performance of the district schools.

### How is the school summary affected?
The school summary remained the same for all schools except Thomas High School. This school experiences a lower reading score, math score and lower overall passing score when we removed the false scores of the 9th graders.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The elimination of the false scores from our analysis negatively affected the overall performance of Thomas High School relative to other schools in question. Thomas High School was the second best school in the district before the analysis in terms of the overall passing percentage. After we removed the false 9th grader's scores, Thomas High School lost its position in the top 5 school ranking in the district. 

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade
The Math and reading score decreased for the overall 9th graders but remained the same for all other grades as they were not affected by our editing. 

#### Scores by school spending
Since Thomas High School was in the $630-$644 spending bucket, the percentages for the passing math, passing reading and overall score all decreased significantly for that specific bucket. However, since our analysis only affected Thomas High School, the rest of the bins did not experience any change in their scores. 

#### Scores by school size
Thomas High School is a medium sized school. Hence, after our replacement of the scores, the passing math percentage, passing reading percentage and the overall passing percentage all decreased for the medium sized bin (1000 - 2000). All points fell by 6% which is a signifcant drop. 

### Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. Thomas High School lost its superior position of being among the top 5 schools in the district. 
2. The overall passing percentage for the medium sized schools that included Thomas High School dropped by a whooping 6%.
3. Since Thomas High School is a charter school, the passing math and reading percentage for all charter schools dropped by approximately 3%.
4. Even though Thomas High School was in the second tier of most expensive schools in terms of spending, removing 9th grader's scores reduced the overall passing percentage of that bin by 9%. That is a very significant drop and had a negative impact on other schools included in that bucket. 
