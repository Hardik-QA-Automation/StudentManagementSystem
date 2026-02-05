# Student Management System (Java Console Application)

## 📌 Overview

The **Student Management System** is a simple Java-based console application designed to manage student records. It allows users to register students, enroll them in courses, search students by ID, display all student details, and sort students by name.

This project demonstrates core Java concepts such as:

* Object-Oriented Programming (OOP)
* Collections (`List`, `ArrayList`)
* Streams and Lambdas
* Input handling using `Scanner`
* Validation using Regular Expressions
* Comparator and sorting

---

## 🛠️ Technologies Used

* **Java** (Core Java)
* **Collections Framework**
* **Java Streams & Lambda Expressions**
* **Regex (Pattern & Matcher)**

---

## 📂 Project Structure

```
com.studentapp
│
├── Main.java      # Application entry point and menu handling
└── Student.java   # Student model with validations and course enrollment
```

---

## 🚀 Features

### 1. Register Student

* Enter student name, age, and student ID
* Enroll student in one or more courses
* Supported courses:

  * Java
  * DSA
  * DevOps

### 2. Find Student by ID

* Search student using a unique student ID
* Displays full student details if found

### 3. List All Students

* Displays information of all registered students

### 4. Sort Students by Name

* Sorts and displays students in alphabetical order

### 5. Exit Application

* Safely exits the program

---

## ✅ Validations

### Student Name

* Only alphabets and spaces allowed

### Student Age

* Must be between **18 and 35**

### Student ID

* Must follow the format:

```
S-1234
```

### Course Name

* Only the following courses are allowed:

```
Java, DSA, DevOps
```

---

## ▶️ How to Run the Project

1. Clone or download the project
2. Open it in any Java IDE (Eclipse, IntelliJ, VS Code)
3. Ensure JDK is installed and configured
4. Run the `Main.java` file

---

## 📸 Sample Console Menu

```
***************** Student Management System *****************
***************** Welcome *****************

1. Register Student details
2. Find student by studentId
3. List All student information
4. List student information in Sorted order
5. Exit
```

---

## 📌 Notes

* This is a **console-based** application
* Data is stored in-memory (no database integration)
* Ideal for beginners learning Java and OOP concepts

---

## 👨‍💻 Author

Hardik Pancha

---

## 📄 License

This project is for learning and educational purposes only.
