# Statement

## 1. Problem Statement
Educational institutions and students often need a simple way to store and manage basic student information without relying on complex databases or graphical interfaces.  
The problem is to design a lightweight, console-based system that allows users to create, view, update, and delete student records while keeping the data persistent between program executions.

---

## 2. Scope of the Project
The scope of this project includes:
- Developing a Java console application that allows users to manage student data.
- Implementing file-based storage using CSV so the data remains available after program exit.
- Structuring the project using multiple layers such as UI, service, DAO, and utility packages.
- Providing basic reporting features like counting students and calculating average age.
- Ensuring simple input validation and error handling.

Out of scope:
- No graphical user interface (GUI).
- No database system (e.g., MySQL, MongoDB).
- No networking or multi-user access.
- No authentication or login features.

---

## 3. Target Users
This project is intended for:
- **Students** learning Java fundamentals such as OOP, file handling, and modular programming.
- **Instructors** evaluating student assignments and Java coding practices.
- **Beginners** who need a simple, easy-to-understand example of a CRUD-based application.

---

## 4. High-Level Features
The system offers the following major capabilities:

###  1. Add Student
Create a new student record with a unique ID, name, age, and course.

###  2. View Students
Display all stored students in a readable format.

###  3. Update Student
Modify the name, age, or course of an existing student using their ID.

###  4. Delete Student
Remove a student record by providing their ID.

###  5. Generate Report
Displays:
- Total number of students  
- Average age  
- Number of students enrolled in each course  

These features cover all basic  operations along with simple reporting functionality.


