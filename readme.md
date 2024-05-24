
Zen Class Programme Database
This MongoDB database is designed to manage the data for a Zen class programme, including users, codekata problems, attendance, topics, tasks, company drives, and mentors.

Collections
Users

Stores user information including their name, email, age, and mentor.
Codekata

Tracks the number of problems solved by each user.
Attendance

Records the attendance status of users on different dates.
Topics

Stores information about the topics covered in the class, including the date they were taught.
Tasks

Contains information about tasks assigned to topics, including their due dates and submission status.
Company Drives

Stores details about company drives, including the date and the students who appeared.
Mentors

Stores information about mentors and their mentees.
Key Queries
Topics and Tasks in October

Retrieves topics and their associated tasks taught in October 2020.
Company Drives in Second Half of October

Finds company drives conducted between 15th and 31st October 2020.
Company Drives and Students Appeared

Retrieves company drives along with the students who appeared for them.
Problems Solved in Codekata

Calculates the total number of problems solved by each user in Codekata.
Mentors with More than 15 Mentees

Finds mentors who have more than 15 mentees.
Absent Users and Unsubmitted Tasks in Second Half of October

Counts the number of users who were absent and did not submit tasks between 15th and 31st October 2020.