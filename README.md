# Pandas-Challenge: School District Performance Analysis

## Background
As the new **Chief Data Scientist** for your city's school district, you have been tasked with helping the school board and mayor make informed decisions regarding future school budgets and priorities. 

For your first task, you are given access to the district-wide standardized test results, including both math and reading scores of students from various schools. Your objective is to aggregate the data and highlight key trends that can drive strategic decisions.

---

## Instructions
This project is broken into several tasks, aimed at providing insights into student performance and school characteristics. Below is a breakdown of the tasks and key areas covered:

### 1. **District Summary**
- Calculate key metrics at the district level:
  - Total number of unique schools
  - Total students
  - Total budget
  - Average math score
  - Average reading score
  - % passing math
  - % passing reading
  - % overall passing (students who passed both math and reading)

### 2. **School Summary**
- Perform calculations to summarize key metrics for each individual school, including:
  - School name
  - School type
  - Total students
  - Total school budget
  - Per student budget
  - Average math score
  - Average reading score
  - % passing math
  - % passing reading
  - % overall passing

### 3. **Highest and Lowest Performing Schools**
- Identify the highest and lowest performing schools by **% Overall Passing**:
  - Sort the schools in descending and ascending order and display the top 5 and bottom 5 schools.
  - Save the results in DataFrames: `top_schools` and `bottom_schools`.

### 4. **Math and Reading Scores by Grade**
- Analyze student scores by grade level (9th, 10th, 11th, 12th) across each school:
  - Create DataFrames to list the average math and reading scores for each grade level.

### 5. **Scores by School Spending**
- Breakdown school performance by average spending ranges (per student):
  - Categorize spending into four bins and calculate mean scores per spending range.
  - Create a DataFrame called `spending_summary` with the relevant data.

### 6. **Scores by School Size**
- Categorize schools based on size (small, medium, large) and calculate average scores per size range.
  - Create a `size_summary` DataFrame that highlights performance based on school size.

### 7. **Scores by School Type**
- Group the data by "School Type" (e.g., charter or district) and calculate performance metrics for each type.
  - Create a DataFrame called `type_summary` that summarizes school performance by school type.

---

## File Structure
- **`PyCitySchools.ipynb`**: Jupyter notebook for the analysis.
- **`school_data.csv`**: Dataset containing school data (students, budgets, types, etc.).
- **`student_data.csv`**: Dataset containing student performance data (scores for math and reading).
- **`Analysis/`**: Folder where results and visualizations are saved.

---

## Requirements
- **Python 3.x** (with libraries such as Pandas, Matplotlib)
- **Jupyter Notebook** (for data analysis and visualization)

