# School-District-Data-Analysis(Using Pandas)

## Background 
The goal is to analyze the district-wide standardized test results. Data is given regarding every student's math and reading scores, as well as various information on the schools they attend. The task is to aggregate the data to showcase obvious trends in school performance.

## Resources 
   * schools_complete.csv: school ID, school_name, type ,size, budget
   
   * students_complete.csv: Student ID, student_name, gender, grade, school_name, reading_score, math_score

## DataFrames: 

### District Summary

High-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

<img width="936" alt="Screen Shot 2023-03-17 at 2 15 03 AM" src="https://user-images.githubusercontent.com/110379358/225841031-37c9c62c-187f-45c7-9a85-f73bb68069c5.png">

### School Summary

DataFrame that summarizes key metrics about each school, including the following:

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

DataFrame that highlights the top 5 performing schools based on % Overall Passing. Includes the following metrics:

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

DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Includes the following metrics:

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

DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

table that breaks down school performance based on average spending ranges (per student). Includes the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size
table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type
table that breaks down school performance based on type of school (district or charter).

## Observable Trends:

* On average, charter schools tend to have higher math and reading scores as well as percent passing math, reading, and overall. 

* Suprisingly, the more a school spends per student, the lower scores are in every category. 
