# School_District_Analysis
In this project we are going to analyze school district data using python(pandas), we will explore how schools performed in regards to their budget, school size, or student scores. 
below is the the plan we are to follow. 
## Plan 
During this analysis we are aiming to perform the below analysis 
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school
## Results: 
- How is the district summary affected?
    - there was a very slight change after removing the data of math and reading from Thomas HS, the difference is about 0.1% for overal passing scores. 
Below is the table for district summary before we replace Thomas High School 9th graders data with NaNs. 
![District Summary before ](https://github.com/elzmanzi/School_District_Analysis/blob/main/Resources/district_summary_before_NaNs.PNG)

Below is the table for district summary after we replace Thomas High School 9th graders data with NaNs. 

![District Summary after ](https://github.com/elzmanzi/School_District_Analysis/blob/main/Resources/district_summary_with_NaNs.PNG)
How is the school summary affected?

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
- Scores by school spending
    - 
![Scores by school spending](https://github.com/elzmanzi/School_District_Analysis/blob/main/Resources/scores%20by%20school%20spending%20per%20student.PNG)
- Scores by school size
    - school size was not reduced, only scores was affected, see the image below
![Scores by school size](https://github.com/elzmanzi/School_District_Analysis/blob/main/Resources/scores%20by%20school%20size.PNG)
- Scores by school type
    - the schools performance by type was not overall affected even after modifying the nineth-grade scores for Thomas High school
        -- explain well
![Scores by school type](https://github.com/elzmanzi/School_District_Analysis/blob/main/Resources/scores%20by%20school%20type.PNG)

## Summary:
 Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.