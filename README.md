ZenTask Database
Welcome to the ZenTask database! This MongoDB database contains information related to a fictional educational platform called ZenTask. ZenTask is designed to facilitate learning and collaboration among students, mentors, and companies.

Database Overview
The ZenTask database consists of the following collections:

zentask: This collection stores information about topics, tasks, company drives, codekata statistics, and student attendance.

mentors: This collection contains data about mentors associated with the ZenTask platform, including their names and the number of mentees they have.

Collections
zentask Collection
The zentask collection is structured as follows:

Topics: Information about various topics, tasks, and assignments scheduled for October.
Company Drives: Details of company recruitment drives, including the participating companies and the students who attended each drive.
Codekata Statistics: Data on the number of problems solved by each student in the codekata section.
Student Attendance: Attendance records of students for the month of October.
mentors Collection
The mentors collection includes documents representing mentors associated with ZenTask. Each document contains the mentor's name and the number of mentees they currently have.

Usage
To access and interact with the ZenTask database, you can use MongoDB commands or libraries compatible with MongoDB such as Mongoose for Node.js.
