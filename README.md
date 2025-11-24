# JAVA-STUDENT-MANAGEMENT-PROJECT
# Student Management System (Console-Based Java Project)

##  Introduction
This project is a simple **Student Management System** built using **core Java**.  
It runs completely in the console and lets you manage student records such as name, age, and course.  
I created this project to practice Java fundamentals like file handling, classes & objects, and modular design.

The system saves student details in a CSV file and loads them every time the program runs, so your data stays safe even after closing the program.

---

##  What You Can Do With This Program
Here’s what the system  supports:

###  Add a New Student  
Enter their name, age, and course.

###  View All Students  
Shows a clean list of all saved student records.

###  Update Details  
Edit any student’s information using their ID.

###  Delete a Student  
Remove any record that you no longer need.

###  View Report  
Shows:
- Total number of students  
- Average age  
- How many students are in each course  

It’s small, simple, and works neatly in the console.

---

##  Project Structure (Folders + Files)::: 
  src/
└── com/example/sms/
├── App.java
├── model/
│ └── Student.java
├── storage/
│ └── FileStorage.java
├── dao/
│ └── StudentDAO.java
├── service/
│ └── StudentService.java
├── ui/
│ └── ConsoleUI.java
└── util/
├── Validator.java
└── ReportGenerator.java

data/
└── students.csv (created automatically)
Each folder has a specific purpose which helped me keep the code organized.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------


