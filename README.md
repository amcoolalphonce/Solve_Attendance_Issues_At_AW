# SOLVE ATTENDANCE ISSUES AT AMERICAN WING, THE UNIVERSITY OF NAIROBI.
***
## Student attendance at the Engineering school faces a lot of issues: 
<br>
                ~Students signing for students who are not in school
<br>
                ~Lectures getting the wrong impression on attendance 
<br>
                ~Discreancies between the attendance and results
***

-> So in this repository I try to come up with logical ways that can be used to prevent such activities from happening.
-> Manual signing can be burdensome and inaccurate, so I think of an automatic system that keeps a track of students attendance and sends it to the lecturers.
-> The system consists of a scanner that students scan their thumbprints on entering the class and after and it calculates the number of hours a student has been in class. The list is automatically sent to the lecturer
***
The step-wise logic of the program is as follows:
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
## 7. Security and Compliance
## 8. Testing and Training
## 9. Deployment
## 10. Feedback and Iteration