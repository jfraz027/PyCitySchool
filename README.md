# PyCitySchool

As the Chief Data Scientist for the city's school district, the goal of was to help the school board and mayor make strategic decisions regarding future school budgets and priorities. The first step was to analyze the district-wide standardized test results. With access to every student's math and reading scores, as well as various information on the schools they attend the the primary goal was to aggregate the data to showcase obvious trends in school performance.

## Work
Using Pandas and Jupyter Notebook as the primary analytical tools of choice, a report was created that included the following data. 

### A District Summary comprised of a high-level snapshot of the district's key metrics listed below:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary including a summarization of key metrics about each school including:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest & Lowest-Performing Schools (by % Overall Passing)
A DataFrame was created for both the top and bottom 5 performing schools based on % Overall Passing. The focus metrics of the analysis included:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math  & Reading Scores by Grade
Date composed of lists for the average math and reading score for students of each grade level (9th, 10th, 11th, 12th) at each school was developed also. 

### Scores by School Spending
Another key analuysis focsed on creating a table that breaks down school performance based on average spending ranges (per student). An important factor was to determine a reasonable cutoff value to group school spending. The table contained thr following metrics table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

The final two analysis centered on

* Scores by School Size categorizing school size as (small, medium, or large) 
* Performance based on type of school (district or charter).

From the various anlysis completed, some key information was determined. Reveiwing the overall passing scores for students in Charter schools were significantly higher than those students in district schools. The overall passing scores of the charter schools averaged around 90 and the district schools were 53. ALso taking a look at the top 5 schools and bottom 5 schools support this in that the top 5 are charter and the bottom 5 are district respectively. One other key trend identifed from the analysis focus on scoring between the different grades. There is very consistent scores for each grade across all schools. The scores on average are -1 or +1 in scoring. The same observations can be identified from reading scores as well. Again, revisitng the overall scores, schools with a lower spending budget yeilded higher scoring. This supports the earlier the difference in Charter and District school scores with Charter spending less but achieving higher scores. 
