# School District Analysis
## Overview of School District Analysis
### A high-level snapshot of the district's key metrics, presented in a table format
### An overview of the key metrics for each school, presented in a table format
### Tables presenting each of the following metrics:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

### Purpose
Analyze school district data based on student funding and students' standardized test scores, to show trends in school performance. This analysis will be used to inform the school board and superintendent in making decisions regarding the school budget allotments.

### Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.9.0, Anaconda 4.9.1, Visual Studio Code 1.49.3

## Results
### How is the district summary affected? How is the school summary affected?
#### School District summary before replacing the Thomas High School ninth graders' math and reading scores.
<img width="800" alt="per_school_summary" src="https://user-images.githubusercontent.com/72039212/98992037-48620100-24f2-11eb-92a2-d3b19fbdf12f.png">

#### School District summary after replacing the Thomas High School ninth graders' math and reading scores.
<img width="802" alt="per_school_summary_updated" src="https://user-images.githubusercontent.com/72039212/98991765-e99c8780-24f1-11eb-94ca-158302d44551.png">

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the Thomas High School ninth grader's math and reading scores increased the ranking of Thomas High School because the math and reading scores reflected higher math and reading score passing percentages. Most notably, Thomas High School is ranked among the top five schools. Which may be attributed to replacing the ninth graders' math and reading score rather than actual student performance.
### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - For math and reading scores by grade, each calculation is limited to data from the respecive grade. Replacing the ninth-grade scores had no affect on the grades of the tenth, eleventh, and twelfth grade scores at Thomas High School or any other High School. 
- Scores by school spending
  - Thomas High School has a budget of $1,043,130 and a per student capita of $638. The increased school performance could potentially affect conclusions made for schools that spend ~$630-$644 per student.
- Scores by school size
  - Thomas High School has 1635 students. Their increased performance could potentially effect conclusions made for schools classified as "Medium" (1000-2000 students).
- Scores by school type
  - Thomas High School is a charter schoool. The reflected increased school performance could potentially affect conclusions made for charter schools. 
## Summary
### Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
Thomas High School passing math percentages were increased from 66.911315% to 93.185690%. The passing reading percentages were increased from 69.663609% to 97.018739%. Lastly, the percentage of students passing both math and reading were increased from 65.076453% to 90.630324%. Replacing the ninth grade reading and math scores improves the performance of Thomas High School compared to other schools in the district and allowed for Thomas High School to be ranked within the to performing schools in the district. The results pose a challenge for having an accurate representation of Thomas High School within the distict. The increased performance results could lead to innacurate conclusions made for charter schools, schools classified as "Medium", and schools that spend $630-644 per student.  
