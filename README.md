🧑‍🎓 Student Grade System
A Python-based Student Grade System that allows you to manage student records, including adding, removing, editing, and searching for students' grades in multiple subjects. Additionally, the system can calculate the average grades for all students.

📋 Features
Student Database Management: View, add, remove, and search student records.

Marks Management: Add or update marks for subjects: Maths, Physics, and Chemistry.

Student Average Calculation: Calculate and display the average grades for all students.

Confirmation for Critical Actions: Confirmation prompts before removing or editing student data to prevent accidental changes.

Interactive Command-Line Interface: User-friendly interface for interacting with the system through a set of options.

🧰 Requirements
Python 3.x

🚀 How to Run
Clone the repository or download the StudentGradeSystem.py file.

Open a terminal or command prompt.

Run the script by typing:

bash
Copy
Edit
python StudentGradeSystem.py
Follow the on-screen prompts to manage student records.

🛠️ Functionality
Available Actions:
1. Show Database: Displays all student records with their marks in Maths, Physics, and Chemistry.

2. Add Student: Allows you to add a new student and input their marks.

3. Remove Student: Allows you to search for a student and delete their record.

4. Search Student Record: Look up a student's details by their name.

5. Edit the Marks: Modify the marks of a specific student in one of the subjects.

6. Average of All Students: Calculate and display the average marks for all students in the database.

7. Exit: Exit the program.

Example Workflow:
Start the program and choose an option (e.g., to add a student).

For adding a student, the system will ask for the student’s name and marks for each subject.

Once added, the new student will appear in the database, and you can perform additional actions like editing or removing data.

⚙️ Code Overview
StudentGradeSystem Class
Attributes:

students: A dictionary to store student names as keys and their marks as a list of values.

Methods:

getMarks(subject): Prompts the user to input marks for a specific subject and ensures the input is valid.

showDatabase(): Displays all student records and their marks.

addStudent(newStudent): Adds a new student to the database with marks input by the user.

removeStudent(removeStudentName): Removes a student from the database after confirmation.

searchStudent(searchStudentName): Searches for a student by name and displays their marks.

editStudent(editStudentName): Edits the marks of an existing student.

findPercentage(): Calculates and displays the average marks for all students in the database.
