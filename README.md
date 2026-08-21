Project Overview: Phase 1 - Student Attendance Tracker
​1. Problem Statement & Objective
​The Problem: Manually tracking daily attendance across multiple classes is tedious and prone to human error. It is also time-consuming to manually calculate percentages and cross-reference them to find students who fall below the required attendance threshold.
​The Objective: Develop an automated, Python-based attendance management system that records daily attendance, calculates overall percentages, automatically identifies defaulters, and generates comprehensive reports using either file handling or a database.
​2. Core Algorithm & Pseudocode
​Step 1 - Initialization: Set up a database or file structure to store student profiles (e.g., Roll Number, Name, Total Classes Conducted, Total Classes Attended).
​Step 2 - Record Daily Attendance: Create an input mechanism to mark students as Present or Absent for the day. Update the "Total Classes Conducted" and "Total Classes Attended" counters accordingly for each student.
​Step 3 - Calculate Percentages: For each student, apply the formula:
(Total Classes Attended / Total Classes Conducted) * 100
​Step 4 - Identify Defaulters: Check the calculated percentage against a predefined minimum threshold (e.g., 75%). If the percentage is lower, flag the student's ID and Name as a defaulter.
​Step 5 - Generate Reports: Compile the attendance records, percentages, and the separated defaulters list, then export this data into a formatted report (e.g., a .txt or .csv file).
