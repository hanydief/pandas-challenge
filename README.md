# Module 4 Challenge - pandas-challenge

In this module, we created and manipulate Pandas DataFrames to analyze school and standardized test data, and below is the analysis report

As a new Chief Data Scientist for the city's school district. In this capacity, we are helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, we been asked to analyze the district-wide standardized test results. based on a given access to every student's math and reading scores, as well as various information on the schools they attend. our task is to aggregate the data to showcase obvious trends in school performance.

Using Pandas and Jupyter Notebook, we created a report that includes the following data. on file named PyCitySchools_starter.ipynb, with some outputs screen captures.

Analysis report contained of District Summary, School Summary, Highest Performing schools by % overall passing, Lowest Performing schools by % overall passing, Math Scores by grade, Reading Score by greade, Scores by school spending, Scores by school size, Scores by school types.

## District Summary:
- Total number of unique schools: 15 school
- The total number of students: 39,170 student
- The total budget: $24,649,428
- The average (mean) math score: 78.99
- The average (mean) reading score: 81.88
- The percentage of students who passed math: 74.98 %
- The percentage of students who passed reading: 85.81 %
- The percentage of students that passed both math and reading: 65.17 %
  
![Model](Solved_Screenshots\District_Summary.png)
## School Summary:
- The total student count per school
- School type (Distrect or Charter)
- The per capita spending "per student budget"
- The total school Budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)
  
![Model](Solved_Screenshots\Per_School_Summary.png)
  
## Highest-Performing Schools by Percentage of Overall Passing
    Schools Sorted by % Overall Passing in descending order as showing below top 5 schools
    - All top 5 schools are charters
    - Total students range between 962 - 1,858 student per school
    - Total school budget range $0.5M - $1.1M
    - School's per student budget range $578 - $$638
    - Overall passing  90.54% - 91.33%
![Model](Solved_Screenshots\Top_Performance_Schools.png)

## Lowest-Performing Schools by Percentage of Overall Passing
    Schools Sorted by % Overall Passing in ascending order as showing below bottom 5 schools
    - All bottom 5 schools are distrect schools
    - Total students range between 2,917 - 4,761 student per school, thats about 3 times charter schools size
    - Total school budget range $1.88M - $3.1M
    - School's per student budget range $637 - $$655
    - Overall passing  52.99% - 53.54%
![Model](Solved_Screenshots\Bottom_Performance_Schools.png)

## Math Scores by Grade
    Math Score Grouped by "school_name" and take the mean of each grade
![Model](Solved_Screenshots\Math_Score_per_School_per_Grade.png)
## Reading Scores by Grade
    Reading Score Grouped by "school_name" and take the mean of each grade
![Model](Solved_Screenshots\Reading_Score_per_School_per_Grade.png)
## Scores by School Spending
    The averages spending ranges by school
![Model](Solved_Screenshots\Scores_by_Schools_Spending_Summary.png)
## Scores by School Size
    Grouping the data by the school sizes
![Model](Solved_Screenshots\Scores_Schools_by_School_Size_Summary.png)
## Scores by School Type
    Grouping schools by "School Type" and average the scoreing results
![Model](Solved_Screenshots\Scores_by_School_Type.png)
## 

# Conclusion Summary:
Mid & Small schools are the top overall passing % are Charter schools with lower average per student budget compared to the Distredt schools that comes toward the bottom of the overall passing % that has averag 53.67% with a large gab with Charter schools that has average 90.43% overall passing rate, considering distrect school size (total students per school) is about 3 times average charter school size (total students per school).

The conclusion Charter Schools has higher education quality for less per student budget but with less school size.
Therefore and based on all above numbers maybe budget plans and schools type should be revised in order to increase education quality by utilizing that budget on more Charter schools and increasing the number of Charter schools vs District schools, and Scores by school spending is a good proof that has student budget < $585 has overall passing 90.37% while schools with student budget $645-$680 has 53.53% overall passing. 