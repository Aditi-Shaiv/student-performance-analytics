# student-performance-analytics 
# Student Performance Analytics System

## About this project
This is my Python project for analyzing student marks and attendance. It calculates each student's total and average marks, assigns a grade, and shows whether the student passed or failed.

## Tools used
- Python
- Pandas
- NumPy
- Google Colab

## Dataset
My dataset has 15 student records. It includes student ID, name, marks in Python, SQL, HTML, CSS and JavaScript, and attendance.

## Rules used
- A+ means an average of 90 or above.
- A means 80 to below 90.
- B means 70 to below 80.
- C means 60 to below 70.
- D means 40 to below 60.
- F means below 40
- A student passes if they score at least 40 in every subject and have at least 75% attendance.

## What the program does
- Shows the student data in a table.
- Calculates average marks.
- Assigns grades and pass/fail results.
- Finds the class average and the highest and lowest averages.
- Calculates the average mark for each subject.
- Shows the top three students.

## How I ran the project
1. I opened my notebook in Google Colab.
2. I ran the cell that creates the student DataFrame and saves `students.csv`.
3. I ran the cell that calculates totals, averages, grades and results.
4. I ran the cell that displays the class and subject analysis.

## Results from my run
- Number of students: 15
- Class average: 78.43
- Highest average: Parvati (97.6)
- Lowest average: Anjali (59.0)
- Passed: 14
- Failed: 1
- Highest-average subject: HTML (81.27)

### Top three performers
1. Parvati — 97.6 (A+)
2. Shiv — 96.4 (A+)
3. Avni — 88.6 (A)
   
## What I learned
I learned how to organize student information in a Pandas DataFrame and calculate totals and averages. I used a function and if/elif conditions to assign grades, and a loop to check pass/fail results. I also learned how to find class and subject averages and sort students to show the top performers.

## Project files
- main.py - Python code
- students.csv - student dataset
- Student_Performance_Analytics.ipynb - Colab notebook
- Project_Documentation.docx - detailed project documentation
