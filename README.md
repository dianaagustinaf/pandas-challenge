# pandas-challenge

In this assignment, I have created and manipulated Pandas DataFrames to analyze school scores and budgets data and showcase trends in school performance.

You can find the analysis notebook [here](PyCitySchools/analysisPyCitySchools.ipynb). In [Resources](PyCitySchools/Resources) are the inicial datasets with every student's math and reading scores, as well as various information on the schools they attend.

- - -

## Report

In this research, data from 15 schools were analysed, with a total of 39,170 students. The total budget for all schools is $24,649,428. Although 85% passed Reading and 75% passed Maths, only 65% passed both subjects.

The best performing school (by overall passing percentage) is Cabrera High School. And the worst performer is Rodriguez High School.

In an analysis of Scores by School Spending, we can observe that the schools with the lowest spending ranges are the ones with the best performance. The group of schools that spends on average $581 per student has an Overall Passing Rate of 90.4%. While the group of schools that spend the most (an average of $650 per student) has a performance of 53.7%.

In addition, this analysis has shown that smaller schools perform better. Small schools have an overall pass rate of 90.3%, medium schools 74.7% and large schools 53.7%.

Finally, according to the analysis by School Type, Charter schools have a much higher performance (90.4%) compared to District schools (53.7%).

- - -

### District Summary

I have created a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

I have created a DataFrame that summarizes key metrics about each school, including the following:

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

### Highest-Performing Schools (by % Overall Passing)

I have created a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Including the following metrics:

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


### Lowest-Performing Schools (by % Overall Passing)

I have created a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Including:

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

### Math Scores by Grade

I have created a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

I have created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

I have created a table that breaks down school performance based on average spending ranges (per student). Including the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

I have created a table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type

I have created a table that breaks down school performance based on type of school (district or charter).

- - -

## References

University of Birmingham / Data Analysis Assignment
