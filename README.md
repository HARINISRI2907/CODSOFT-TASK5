# 🎓 Student Management System

![Java](https://img.shields.io/badge/Language-Java-blue.svg)
![License](https://img.shields.io/badge/License-Educational-informational)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

A simple console-based *Student Management System* built with Java as part of *CODSOFT Task*.

## 📌 Overview

This project simulates a basic student management system.  
You can add, view, update, and remove student records through a text-based menu.

The system demonstrates the use of:
- Java classes & objects
- Collections (e.g., ArrayList)
- User input handling with Scanner
- Basic CRUD (Create, Read, Update, Delete) operations

## ✨ Features
✅ Add new student records  
✅ View list of all students  
✅ Update student details  
✅ Remove student records  
✅ Menu-driven console interface  
✅ Simple and beginner-friendly design

## 🧩 How It Works (Logic)

- Display a main menu with options:
  - 1️⃣ Add Student
  - 2️⃣ View Students
  - 3️⃣ Update Student
  - 4️⃣ Remove Student
  - 5️⃣ Exit
- Use Scanner to capture user input.
- Store student data in a list (e.g., ArrayList).
- For each operation:
  - Add: Create a new student object and add it to the list.
  - View: Loop through the list and display each student’s details.
  - Update: Find the student by ID or name and modify details.
  - Remove: Find and delete the student from the list.
- Continue showing the menu until the user exits.

> Note: Data will be reset when the program restarts (no database or file persistence yet).

## ⚙ How to Run
Make sure you have Java installed.

# Clone the repository
git clone https://github.com/HARINISRI2907/StudentManagementSystem.git

# Go to project directory
cd StudentManagementSystem

# Compile the Java program
javac StudentManagementSystem.java

# Run the program
java StudentManagementSystem

> Replace StudentManagementSystem.java with the actual filename if it’s different.

📂 Project Structure

StudentManagementSystem.java – Java source code containing the logic.
StudentManagementScreenshot.png – Screenshot of the running program (if you have one).

🔮 Future Improvements

🚀 Add file or database storage to keep data permanently
🚀 Support searching students by different fields
🚀 Sort students by name, grade, etc.
🚀 Add GUI using Java Swing or JavaFX
🚀 Track additional details like courses, grades, and attendance

🛠 Technologies Used
Java (console application)
Scanner (for user input)
ArrayList or similar data structures

✏ Author
HARINISRI2907

📄 License
This project is created for educational purposes.

