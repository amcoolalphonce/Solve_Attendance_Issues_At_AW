# SOLVE ATTENDANCE ISSUES AT AMERICAN WING, THE UNIVERSITY OF NAIROBI.
***
## Table of Contents
[Issues ](#issues)
1. [Hardware Setup](#1-hardware-setup)
2. [Database Setup](#2-database-setup)
3. [Attendance Software](#3-attendance-software)
4. [Attendance Calculation](#4-attendance-calculation)
5. [Integration with student portal](#5-integration-with-student-portal)
6. [Attendance reporting for Instructors](#6-attendance-reporting-for-instructors)
7. [Security and Compliance](#7-security-and-compliance)
8. [Testing and Training](#8-testing-and-training)
9. [Deployment](#9-deployment)
10. [Feedback and Iteration](#10-feedback-and-iteration)
[Solutions](#solutions)

### Issues
<br>
                * Students signing for students who are not in school
<br>
                * Lectures getting the wrong impression on attendance 
<br>
                * Discreancies between the attendance and results
***

### Solutions
-> So in this repository I try to come up with logical ways that can be used to prevent such activities from happening.
-> Manual signing can be burdensome and inaccurate, so I think of an automatic system that keeps a track of students attendance and sends it to the lecturers.
-> The system consists of a scanner that students scan their thumbprints on entering the class and after and it calculates the number of hours a student has been in class. The list is automatically sent to the lecturer
***
The step-wise logic of the program is as follows:
### System flow chart
## 1. Hardware Setup
Buy biometric thumb scanners and place them at the entance of the class before the class begins
Connect the scanners to a central server/database where attendance can be stored
## 2. Database Setup
Access the Student Management Information System database to have every student's and lecturers's data. Specify the database to Engineering Department only and further divide it into the different Faculties(Where Electrical has its own and Civil  also has its own etc...)
## 3. Attendance software
Create software that interfaces with the thumbprint scanners, captures thumbprint data, and records attendance information
Implement real-time processing: Ensure that attendance data is processed in real-time to provide instant feedback on a student's attendance status
## 4. Attendance Calculation
Record entry and exit times: Capture the thumbprint data when a student enters and exits the classroom to record their attendance times
Calculate attendance duration by subtracting the exit time from the entry time
## 5. Integration with Student Portal
Develop a student portal: Create an interface where students can access their attendance records
Provide attendance summaries: Display attendance summaries, including total hours attended, on the student portal for each student
## 6. Attendance Reporting for Instructors
Develop an instructor interface: Create a separate interface for instructors to view and manage attendance records for their classes
Generate attendance reports: Allow instructors to generate attendance reports for specific time periods, individual students, or entire classes
## 7. Security and Compliance
Implement data security measures: Ensure that thumbprint data and attendance records are stored securely to protect student privacy.
## 8. Testing and Training
Test the system: Conduct thorough testing to ensure the accuracy and reliability of the thumbprint-based attendance system.
Provide training: Train students, instructors, and administrative staff on how to use the system effectively.
## 9. Deployment
Install the system.Deploy the thumbprint-based attendance system in classrooms after successful testing and training.
Monitor and troubleshoot.Implement a monitoring system to identify and address any issues that may arise during regular use
## 10. Feedback and Iteration
Gather feedback. Collect feedback from students, instructors, and staff to identify areas for improvement.
Iterate on the system:Make necessary adjustments and improvements based on feedback to enhance the overall effectiveness and user experience of the attendance system.