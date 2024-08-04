# pandas-challenge

**Scenario**
<p>You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.</p>

<hr></hr>

**District Summary**
  - [x] Calculate the total number of unique schools
  - [x] Calculate the total number of students
  - [x] Calculate the total budget
  - [x] Calculate the average (mean) math score
  - [x] Calculate the average (mean) reading score
  - [x] Use the code provided to calculate the percentage of students who passed math
  - [x] Calculate the percentage of students who passed reading
  - [x] Use the code provided to calculate the percentage of students that passed both math and reading
  - [x] Create a new DataFrame for the above calculations 

**School Summary**
  - [x] Use the code provided to select the school type
  - [x] Calculate the total student count
  - [x] Use the code provided to calculate the per capita spending
  - [x] Calculate the average test scores
  - [x] Calculate the number of schools with math scores of 70 or higher
  - [x] Calculate the number of schools with reading scores of 70 or higher
  - [x] Use the provided code to calculate the schools that passed both math and reading with scores of 70 or higher
  - [x] Use the provided code to calculate the passing rates
  - [x] Create a new DataFrame for the above calculations 

**Highest-Performing Schools by Percentage of Overall Passing**
  - [x] Sort the schools by % Overall Passing in descending order
  - [x] Save the results to a DataFrame called top_schools
  - [x] Display the first 5 rows

**Lowest-Performing Schools by Percentage of Overall Passing**
  - [x] Sort the schools by % Overall Passing in ascending order
  - [x] Save the results to a DataFrame called bottom_schools
  - [x] Display the first 5 rows

**Math Scores by Grade**
  - [x] Use the code provided to separate the data by grade
  - [x] Group by "school_name" and take the mean of each
  - [x] Use the code to select only the math_score
  - [x] Combine each of the scores above into a single DataFrame called math_scores_by_grade

**Reading Scores by Grade**
  - [x] Use the code provided to separate the data by grade
  - [x] Group by "school_name" and take the mean of each
  - [x] Use the code to select only the reading_score
  - [x] Combine each of the scores above into a single DataFrame called reading_scores_by_grade

**Scores by School Spending**
  - [x] Use pd.cut with the provided code to bin the data by the spending ranges
  - [x] Use the code provided to calculate the averages
  - [x] Create a DataFrame using the binned and averaged spending data

**Scores by School Size**
  - [x] Use pd.cut with the provided code to bin the data by the school sizes
  - [x] Use the code provided to calculate the averages
  - [x] Create a DataFrame using the binned and averaged size data

**Scores by School Type**
  - [x] Group the per_school_summary DataFrame by "School Type" and average the results
  - [x] Use the code provided to select the new column data
  - [x] Create a new DataFrame called type_summary that uses the new column data

**Written Report**
  - [x] Summarizes the analysis
  - [x] Draws two correct conclusions or comparisons from the calculations

<hr></hr>

## References

Below is a list of references that were utilized during the development of this project:

1. **Official Documentation**
   - [Pandas Documentation](https://pandas.pydata.org/docs/) - Used extensively for data manipulation and analysis, including functions for data cleaning, transformation, and aggregation.
   
   - [Pathlib Documentation](https://docs.python.org/3/library/pathlib.html) - Utilized the `Path` module for handling file system paths in a more intuitive and object-oriented manner.
   
   - [Warnings Library Documentation](https://docs.python.org/3/library/warnings.html) - Employed to manage and filter warnings generated during runtime, ensuring cleaner output and error handling.
2. **Other Repositories**
  - [bdthai81 Pandas Challenge](https://github.com/bdthai81/pandas-challenge) - Used git repository for reference for some calculations when I got stuck on them. 