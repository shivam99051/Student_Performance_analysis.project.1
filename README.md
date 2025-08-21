Title: 
Student Performance Analysis Using Python.

Description: 
The purpose of this project is to use Python to analyze and visualize students' academic performance. Students' names and subject-specific grades are taken from a sizable CSV dataset from kaggle.

Objectives: 
Process and import student information from a CSV file.
Handle missing or invalid values.
Calculate each student's average and total grades.
Based on the average score, assign grades.
Identify the class average and top performer.
Use matplotlib to visualize top students.
Save the completed report as a CSV file.
Installation
How To Run:
Use a terminal/command prompt and run: python student_analysis.py

You need Python installed.

Install Required Libraries: pip install pandas. pip install matplotlib.

Input Format
The program expects a CSV file with the following structure:

Name,Subject1,Subject2,Subject3
Alice,85,90,88
Bob,78,67,74
Charlie,92,95,91
...

## Output Details

- Student summary printed in the terminal (first 10 students)
- Class average displayed
- Topper identified by highest average
- A bar chart showing top 20 students by average marks
- Final results saved to: `final_student_report.csv`

## Grade table 

| Average Score | Grade |
|---------------|-------|
| 90 and above  | A     |
| 75–89         | B     |
| 50–74         | C     |
| Below 50      | F     |

## Sample Output
 Sample Student Summary (First 10 Rows):

Name|Subject1|Subject2|Subject3|Total|Average|Grade
Alice,85,90,88,263,87.67,B
Bob,78,67,74,219,73.00,C
...
...
class Average Marks: 81.42
Topper: Charlie | Average: 92.67 | Grade: A




## Visualistaion

The program displays a bar graph of the top 20 students based on average marks:
- **X-axis**: Student Names
- **Y-axis**: Average Marks
- Readability is improved by visual aids like gridlines and rotated labels.

##  Project Structure:
student performance analysis
├── student_Performance_analysis.py # Main program s
├── students_reports.csv # CSV file
├── final_student_report.csv # Output CSV file
├── README.md # Documentation
└── screenshots/ # Graph/image exports


## Author Info

**Shivam Raj**  
Bsc(CSDA) Student | [IIT PATNA]  
Review 1 Submission – Data Science Project (Project 1)
