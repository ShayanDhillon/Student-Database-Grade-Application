# Student-Database-Grade-Application

The application’s main objective is to provide a way to get information about students and courses in a quick and efficient manner.

Below are the explanations for each feature:

To start off, the application gives the user directions on how to open the main user form on its main page.
This form does 5 main things: Importing data into a worksheet, Listing the courses available in the data, Listing each student in course (chosen by user), Displaying a course’s average, and finally it can generate a word document with stats about the data.

Clicking ‘Display Class Average’ at any point (after importing data), will prompt the user to pick a course, and following a valid selection, it will show the user the average of each assignment and exam for the selected course.

When you select ‘Import data’ and click continue, you are prompted to select a file.
After selecting the Registrar.mdb file, it will import all the data needed into the “Data” worksheet.

When you click ‘List courses’, it will prompt you with another file selection, and after selecting Registrar, it will open a worksheet and list out all distinct courses in the database.

When clicking ‘Course Enrollment’ and "Continue", firstly it will check if data has been imported, and if it has, it will ask for a course from the user (using an input box). After a valid course has been picked, a worksheet will be created with a list of all students in the course. 

Finally, selecting ‘Generate Report’ and hitting continue (assuming data has been imported) will create a multiple page report (using word) on the data.
