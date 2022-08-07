# School_District_Analysis

## Project Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources 
Data Source: schools_complete.csv, students_complete.csv

Software: Jupyter Notebook

## Overview of the school district analysis:
The purpose of this school district analysis is to read the election results from csv files (school and student data) and complete necessary tasks for analysis. The first task was to replace the reading and math scores for Grade 9 from Thomas High School with NaN. The next task was to find the following metrics: 
- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

## School District Results: 
How is the district summary affected?
- Very slight decrease in % Overall Passing

How is the school summary affected?
- Remains the same for all other school except Thomas High school

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- No signaficant changes in replacing the ninth graders’ math and reading scores

Upon replacing the night grader's math and reading scores:

- Math scores by grade
<img width="344" alt="Screen Shot 2022-08-06 at 9 36 57 PM" src="https://user-images.githubusercontent.com/104872971/183271369-87e9c3ff-9088-4c42-8964-b12080f565e8.png">

- Reading scores by grade
<img width="342" alt="Screen Shot 2022-08-06 at 9 37 15 PM" src="https://user-images.githubusercontent.com/104872971/183271380-fd22459e-dbea-4106-bd78-274aef658fdd.png">

- Scores by school spending
<img width="700" alt="Screen Shot 2022-08-06 at 9 39 49 PM" src="https://user-images.githubusercontent.com/104872971/183271411-7aff1bb2-6314-48da-bac8-61cce13d66f1.png">

- Scores by school size
<img width="643" alt="Screen Shot 2022-08-06 at 9 41 00 PM" src="https://user-images.githubusercontent.com/104872971/183271433-5c8b9b39-164c-422c-ac9d-5a06bd00b89d.png">

- Scores by school type
<img width="605" alt="Screen Shot 2022-08-06 at 9 41 36 PM" src="https://user-images.githubusercontent.com/104872971/183271443-75928d2b-8173-4bd9-8999-a6f745ab0b45.png">
