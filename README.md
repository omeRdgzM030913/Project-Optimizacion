# Project-Optimizacion
This is a project focused on optimizing class scheduling. The main objective is to minimize the costs associated with the assignment of teachers, subjects, classrooms and schedules, taking into account key restrictions such as the availability of teachers and the schedule capacity of each one.

General Description

Objective:
Design an automated system that allows the user to enter unavailable teachers or schedules and, based on this, recalculate the optimal schedule.
Minimize costs based on parameters such as teacher rates, subject complexity, classroom usage, and hours.

Linear Programming (LP) Methodology:
Binary variables are formulated that indicate whether “a teacher X teaches subject Y at time Z in classroom W.”
The objective function adds the costs of each assignment (teacher, subject, schedule, classroom) and searches for the minimum assignment.
The constraints ensure that each subject is assigned exactly once, that a teacher is not in two places simultaneously, and that the same classroom is not occupied more than once in the same schedule.

Python Tools and Libraries:
pandas: To read and manipulate data from Excel files.
pulp: To formulate and solve the Linear Programming model.
openpyxl: Creation and editing of a final Excel with the optimal solution.
English:os: To automatically open the Excel file containing the resulting assignment.

User Interaction:
The script allows you to remove unavailable teachers or schedules. Data structures are modified in real time, ensuring that the final solution respects these new restrictions.
Upon completion, the optimal solution is printed on the console and an Excel file is generated with a detailed summary (teacher, subject, classroom, schedule, individual costs, and total cost).

Results:
The program returns a feasible assignment that meets all academic criteria (subject, availability, costs, etc.).
It also offers transparency in decision making, showing how much each component contributes to the overall cost.

My Qualities in Data Science

Mathematical Modeling: Formulation of problems using Linear Programming (definition of variables, objective function, and restrictions).

Data Manipulation: Reading and preprocessing information in Excel with pandas.

Optimization: Use of specialized libraries (pulp) to solve complex Scheduling problems.

Automation and Reporting: Automatic generation of Excel reports and clear deployment of the solution.

Flexibility and Scalability: Modular design that allows adaptation to different scenarios (changes of teachers, subjects or restrictions).

This project demonstrates my ability to combine data analytics, mathematical optimization and Python programming for practical purposes and tangible impact on the organization of academic resources.
