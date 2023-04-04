# PyCity Schools

## Background
In this challenge, you are the new Chief Data Analyst that is responsible for helping the school board make decisions on budgeting and priorities based on student performance. Provided are the students standardized scores, where we can observe the trends in school performance. The resources used comprised of two csv datasets. schools_complete.csv included Student ID, school_name, type, size, and budget. students_complete.csv included Student ID, student_name, gender, grade, school_name, reading_score and math_score. Both datasets were imported and merged. 
  

## Results/Observations
The dataset includes a total of 15 schools and 39,170 students The average math score was 79 and the average reading score was 82. More students were successful at passing in reading (86%) than math (75%). The overall passing reate was 65%.

Out of the 15 schools presented, 7 of them were District schools and 8 were Charter schools. Total students ranged from 427 students to 4,976 with District schools having more students overall than Charter schools.

Total budget for each school showed the amount of money each school had to spend on school performance resources. The budget ranged from $248,087.00 at Holden High School to $3,124,928.00 at Bailey High School. 

Overall, Charter schools surpassed the District schools in all metrics. The Highest Performing schools were all Charter schools and the Lowest Performing schools were all District schools. However, more analysis will be required to determine if the effect is due to school practices or the fact that Charter schools tend to serve smaller student populations.

Another trend is that larger school size and higher budget did not reflect higher test scores. The lower spending ranges (per student: <$585 - 630) and smaller school size (<1000 - 2000) were more successful. When student size and budget increases, it negatively influenced student achievement. 

Refer to PyCitySchools_starter.ipynb in the PyCitySchools folder for the following results: 
* District Summary
* School Summary
* Highest-Performing Schools (by % Overall Passing)
* Lowest-Performing Schools (by % Overall Passing)
* Math Scores by Grade
* Reading Scores by Grade
* Scores by School Spending
* Scores by School Size
* Scores by School Type
