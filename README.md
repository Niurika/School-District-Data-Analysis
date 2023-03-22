# School-District-Data-Analysis(Using Pandas)

## Background 
The goal is to analyze the district-wide standardized test results. Data is given regarding every student's math and reading scores, as well as various information on the schools they attend. The task is to aggregate the data to showcase obvious trends in school performance.

## Resources:  
   * schools_complete.csv: school ID, school_name, type ,size, budget
   
   * students_complete.csv: Student ID, student_name, gender, grade, school_name, reading_score, math_score

##Built With:
  *Jupyter Notebook
  *Python
  *Pandas
  
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

<img width="1109" alt="Screen Shot 2023-03-17 at 2 33 58 AM" src="https://user-images.githubusercontent.com/110379358/225841440-8e423609-b016-4ec4-a67d-b049138e45ac.png">

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

<img width="1106" alt="Screen Shot 2023-03-17 at 2 34 48 AM" src="https://user-images.githubusercontent.com/110379358/225841590-d0d8c913-05fb-4852-8e13-e0d294d2abec.png">

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

<img width="1101" alt="Screen Shot 2023-03-17 at 2 35 31 AM" src="https://user-images.githubusercontent.com/110379358/225841798-56464c03-31cc-46dd-96df-cd63c86933e7.png">

### Math Scores by Grade

DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="485" alt="Screen Shot 2023-03-17 at 2 39 37 AM" src="https://user-images.githubusercontent.com/110379358/225842395-e3a1dede-cd54-4a79-9317-80030bf2e040.png">

### Reading Scores by Grade

DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="479" alt="Screen Shot 2023-03-17 at 2 40 01 AM" src="https://user-images.githubusercontent.com/110379358/225842459-1154655f-06d2-48b5-947b-e2ae27740f91.png">

### Scores by School Spending

table that breaks down school performance based on average spending ranges (per student). Includes the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

<img width="869" alt="Screen Shot 2023-03-17 at 2 40 51 AM" src="https://user-images.githubusercontent.com/110379358/225842609-0fb4f8ca-1840-44b9-833e-1dca8f39df4e.png">

### Scores by School Size
table that breaks down school performance based on school size (small, medium, or large).

<img width="801" alt="Screen Shot 2023-03-17 at 2 42 38 AM" src="https://user-images.githubusercontent.com/110379358/225842899-c8752ca1-a728-4816-92c2-5da1430822e4.png">

### Scores by School Type
table that breaks down school performance based on type of school (district or charter).

<img width="751" alt="Screen Shot 2023-03-17 at 2 43 10 AM" src="https://user-images.githubusercontent.com/110379358/225843029-6087ec09-77c8-43fb-8e10-0488b46d4e41.png">

## Observable Trends:

* On average, charter schools tend to have higher math and reading scores as well as percent passing math, reading, and overall. 

* Suprisingly, the more a school spends per student, the lower scores are in every category. 
