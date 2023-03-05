# Assignment Step Description

Read the given set of questions and solve them by writing queries using SQL Server
The estimated effort to complete this assignment is 2 - 3 hours
** Things to do **
* Clone the boilerplate
* Create sql queries based on the problem statement and expected solution
* Write all queries in the given queries.json file in Sequence and key names.
* Add that to the boilerplate that you have cloned and push it to gitlab 
  ( Note: You should have a new repo created in gitlab where it has to be pushed)
* Submit the assignment in Hobbes for evaluation and share score with your mentor.

## Problem Statement
Note management app (similar to Google Keep) is used to take notes, add notes into categories and set reminders for a note. Create the necessary DB schema (SQL Server) including tables, relationships and add sample data into each table.

### Expected Solution
* Create the tables for Note, Category, Reminder, User, NoteReminder and NoteCategory.
* User table fields: user_id, user_name, user_added_date, user_password, user_mobile
* Note table fields: note_id, note_title, note_content, note_status, note_creation_date
* Category table fields : category_id, category_name, category_descr, category_creation_date, category_creator
* Reminder table fields : reminder_id, reminder_name, reminder_descr, reminder_type, reminder_creation_date, reminder_creator

Insert the rows into the created tables (Note, Category, Reminder, User, NoteReminder and NoteCategory) as per attached snapshot(Data_Snapshot.docx).

Write the queries to carry out the below listed operations:

1.	Fetch the row from User table with Id=112233 and Password=’Maya1214’.
2.	Fetch all the rows from Note table with note_creation_date=’01/31/2019’.
3.	Fetch all the Categories created after ‘01/22/2019’.
4.	Fetch all category details which belongs to note with note id=1.
5.	Fetch all the Notes from the Note table with userId=112244.
6.	Fetch all the Notes from the Note table for category_id=1.
7.	Fetch all the reminder details for note id=2.
8.	Write a query to change the note_status to ‘Completed’ with note Id=3.
9.	Write a query to set a reminder of type ‘Personal Reminders’ for Note with note id=1. [Find reminder id based upon reminder_type]
