# pandas-challenge
Create and manipulate Pandas DataFrames to analyze school and standardized test data
# Unit 4 Homework: Pandas, Pandas, Pandas
In this assignment, you’ll create and manipulate Pandas DataFrames to analyze school and standardized test data.

## Instructions

Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

### District Summary

Create a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)
-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* More students in the district are passing reading than passing math. 
* More students in the district have a lower average math score than reading score.
* There are 15 total schools in the district based on the data provided.

### School Summary

Create a DataFrame that summarizes key metrics about each school, including the following:

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
-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* The percentage of students passing both reading and math from the different schools in the district vary from 53% to 91.3%.
* Largely, the Charter schools have a higher percentage of students passing both reading and math than their District counterpart schools.
* The schools have varying budgets depending on how many students go to their school. 
* While the schools do not have all the same per student budget, the budget is not more per student in charter schools than it is for district schools.
* The charter schools have less total students than the District counterpart schools.


### Highest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:

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
-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* The top 5 performing schools based on % of students who passed math and reading (% Overall Passing) are all charter type schools.
* Cabrera High School has the highest % Overall Passing students.


### Lowest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:

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
-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* The bottom 5 performing schools based on % of students who passed math and reading (% Overall Passing) are all district type schools.
* Rodriguez High School has the lowest % Overall Passing students.

### Math Scores by Grade

Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* The average math scores vary more by school than by grade level.
* The 12th grade average math scores across schools in the district is more than 76%.

### Reading Scores by Grade

Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* The average reading scores vary more by school than by grade level.
* The 12th grade average reading scores across schools in the district is more than 80%.

### Scores by School Spending

Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

-----------------------------------------------------------------------------------------------------------

Observable trends from the data:

* Schools that spent less than $585 per student had higher %overall passing.
* Schools that spent more per student had a lower percentage of students passing math and reading.

### Scores by School Size

Create a table that breaks down school performance based on school size (small, medium, or large).

-----------------------------------------------------------------------------------------------------------
Observable trends from the data:

* Larger schools, defined as the total number of students being more than 2000, have a lower percentage of students passing math and reading.
* Small schools, defined as <1000 total students and medium schools, defined as between 1000-2000 students, showed similar percentage of students passing math and reading.


### Scores by School Type

Create a table that breaks down school performance based on type of school (district or charter).

-----------------------------------------------------------------------------------------------------------
Observable trends from the data:

* Charter type schools have a higher percentage of students passing math, passing reading, and passing both math and reading in comparison to their district school counterparts.
* Charter type school students have average math and reading scores that are higher than their district school student counterparts.

### Submission
On [Bootcamp Spot](https://bootcampspot-v2.com), submit a link to the `pandas-challenge` repo that you created for this assignment. Be sure to include a `README.md` file in addition to the Jupyter Notebook that contains your report.

## Rubric

[Unit 4 Homework Rubric](https://docs.google.com/document/d/1VwP0gfKN-ZGZvIhuaKmx00wCcPOMC5qofXXFcUGe90E/edit?usp=sharing)

- - -

## References

Data generated by Mockaroo, LLC. (2021) Realistic Data Generator. [https://www.mockaroo.com/](https://mockaroo.com/). Modified by Trilogy Education Services, LLC.

- - -

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
