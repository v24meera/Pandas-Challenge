# pandas-challenge

In this assignment, you’ll create and manipulate Pandas DataFrames to analyze school and standardized test data.
Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.
Hint: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.

**District Summary**
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

**Include the following:**
-Total number of unique schools
-Total students
-Total budget
-Average math score
-Average reading score
-% passing math (the percentage of students who passed math)
-% passing reading (the percentage of students who passed reading)
-% overall passing (the percentage of students who passed math AND reading)

**School Summary**
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:
-School name
-School type
-Total students
-Total school budget
-Per student budget
-Average math score
-Average reading score
-% passing math (the percentage of students who passed math)
-% passing reading (the percentage of students who passed reading)
-% overall passing (the percentage of students who passed math AND reading)

**Highest-Performing Schools (by % Overall Passing)**
-Sort the schools by % Overall Passing in descending order and display the top 5 rows.
-Save the results in a DataFrame called "top_schools".

**Lowest-Performing Schools (by % Overall Passing)**
-Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
-Save the results in a DataFrame called "bottom_schools".

**Math Scores by Grade**
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Reading Scores by Grade**
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Scores by School Spending**
-Create a table that breaks down school performance based on average spending ranges (per student).
-Use pd.cut to categorize spending based on the bins.
Include the following metrics in the table:
-Average math score
-Average reading score
-% passing math (the percentage of students who passed math)
-% passing reading (the percentage of students who passed reading)
-% overall passing (the percentage of students who passed math AND reading)

**Scores by School Size**
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

**Scores by School Type**
-Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
-This new DataFrame should show school performance based on the "School Type".

**Reference:**
- In completing this assignment, I referenced a variety of supplementary resources to clarify coding concepts and enhance my understanding of data analytics techniques. 
Due to limited availability of tutoring support during my work hours, I consulted platforms such as Google, YouTube, ChatGPT, and reputable data analytics sites like GeeksforGeeks, Kaggle, and Stack Overflow. 
I also utilized AI tools for coding assistance and guidance on specific coding challenges, which provided additional clarity and support for troubleshooting issues outside of standard support hours.

- The code and analyses presented in this assignment are authored by me, with these external resources and AI tools used strictly for educational and guidance purposes. 
This disclosure is intended to provide transparency to the grading staff, ensuring they understand the context of my consultations with external resources and that my work reflects my independent efforts.