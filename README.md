# School_District_Analysis

## Background: 

### Overview of the school district analysis:

Maria is a Cheif data scientist for a city school district. She is responsable for analysing all standard test data and presenting performance trends and patterns to the board.

Her insights are used to inform discussions and strategic decisions at the school and district level.

In this analysis Maria has been informed that the math & reading scores in a specific school (Thomas High School) in the city school district has been compromised and that scores are tampered with. Therefore removing the scores for ninth graders in Thomas High School is manadatory in order to represent geniun results, trends and reccomendations which will help the board make strategic decisions.

### Purpose:
I will help Maria analyse data on student funding and student standarized test scores. I am given access to students math and reading scores as well as various information on schools they attend. I have to agregate the data and showcase trends in school performance. I will first remove the grade nine scores for Thomas High School and then perform my analysis on district level and per school level.

This analysis will assist the school board in making decisions regarding the school budgets in priorities. 

## Results:

### How is the district summary affected?

After removing the grade 9 math and reading scores and replacing it with Nan we can notice the following:

- The affect on district level is around 1% lower in the Passing math %, Passing reading % and Overall passing %. This can be explained by the fact that 9th graders in Thomas High school are 461 students compared to the total number of students across the district of 39170 students. Therefore removing the 9th graders scores in that specific school will not represent a great impact on district level. 

Kindly refer to the below images for comparison.

### How is the school summary affected?
When comparing on a per school level we can notice that the Thomas High school Passing math, reading and overal percentage has incdreased dramatically as showing in image below: 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 
When replacing the grade 9 scores with NaNs you can notice a significant decrease in the percentages specifically for Thomas High School as follows:
- % Passing Math decreased around 26%
- % Passing Reading decreased around 27%
- % Overall Passing decreased around 26%

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade**


As shown above in the summary tables the grade nine math and reading scores for Thomas High School display NaN after running the code whereas the remaining data remained intact.

If we had not removed the grade 9 scores for Thomas High School the averages of scores and the percentages of passing would have been affected slightly for the 9th graders across the district and significantly impacted on per school level where the overal passing percentage for the Thomas High School has changed drastically. Remember, representing reliable and genuin data/results is far more important than just presenting a readable table/results.

#### Scores by school spending**

- % Passing Math decreased by 6%
- % Passing Reading decreased by 7%
- % Overall Passing decreased by 7%

#### Scores by school size**

- % Passing Math decreased by 8%
- % Passing Reading decreased by 6%
- % Overall Passing decreased by 6%

#### Scores by school type**

- % Passing Math decreased by 4%
- % Passing Reading decreased by 4%
- % Overall Passing decreased by 3%


