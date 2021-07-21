# School District Analysis

# Overview of the school district analysis: Explain the purpose of this analysis.

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 

She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


# Results: Using bulleted lists and images of DataFrames as support, address the following questions.
-  How is the district summary affected?

There was a slight impact to the district summary categories after adjustments were made to Thomas High Schools 9th grade data.

Before Adjustments:
<img width="942" alt="DF - Pycity" src="https://user-images.githubusercontent.com/691355/126548138-2b9fc7c8-c97e-4223-9fa5-01a09dbd68fd.png">

After Adjustments:
<img width="933" alt="DF-Challenge" src="https://user-images.githubusercontent.com/691355/126548167-a5bc0d06-d253-4855-94de-9e743c9e37de.png">

All the impacted categories saw (<1%) change.

Average Math Score decreased from 79% to 78.9%.
Average Reading score stayed the same at 81.9%
Passing Math score decreased from 75% to 74.8%
Passing Reading % decreased from 85.8% to 85.7%.
Overall Passing % decreased from 65.2% to 64.9%.

-  How is the school summary affected?

The school summary saw a greater increase in percentages after only 10th-12th grader data was added to the per school summary.

Before Adjustments: 9th Grader Data w/Nan
<img width="999" alt="DF - ps - before" src="https://user-images.githubusercontent.com/691355/126552191-d8cb6a2d-3c8e-4a7c-9e0a-9ac65b88f184.png">

After Adjustments: 10th-12th Grade Data Only
<img width="987" alt="DF - ps - After" src="https://user-images.githubusercontent.com/691355/126552220-bacf6992-70b6-4566-bca8-0a3b5e918cdf.png">


-  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


-  How does replacing the ninth-grade scores affect the following:

#Math and reading scores by grade
#Scores by school spending
#Scores by school size
#Scores by school type
#Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced #with NaNs.
