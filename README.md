# student-management
# 📚 Student Management System (Python)

A simple **Student Management System** built using Python.
This is a command-line project that allows you to **add, update, delete, and list students** with data stored permanently in a JSON file.

It is designed as a beginner-friendly project to practice:

* Python OOP (Classes & Objects)
* File handling
* JSON data storage
* Lists & iteration
* Basic CRUD operations

---

## 🚀 Features

* Add new student
* Update existing student
* Delete student
* List all students in table format
* Prevent duplicate student IDs
* Persistent storage using JSON file
* Simple menu-driven interface

---

## 🛠️ Technologies Used

* Python 3
* JSON (for data persistence)
* OOP concepts (Classes & Methods)
* Standard Python libraries (`json`, `os`)

---

## 📂 Project Structure

```
student_manager.py
students.json   (auto-created when you add first student)
README.md
```

---

## ▶️ How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
```

### 2️⃣ Run the program

```bash
python student_manager.py
```

---

## 🧭 Menu Options

When you run the program, you will see:

```
===== Student Management System =====
1. Add Student
2. Update Student
3. Delete Student
4. List Students
5. Exit
```

Choose an option by entering a number (1–5).

---

## 💾 Data Storage

* Student data is stored in **students.json**
* File is automatically created if it does not exist
* Data format example:

```json
[
    {
        "id": "101",
        "name": "Karan",
        "grade": "A"
    }
]
```

---

## 🧱 Class Design

### Student Class

Represents a single student:

* id
* name
* grade
* to_dict() for JSON conversion

### StudentManager Class

Handles:

* Loading & saving data
* Add / Update / Delete operations
* ID validation
* Displaying student list

---

## 🎯 Learning Outcomes

This project helps you practice:

* Python classes and constructors
* List operations
* File read/write
* JSON serialization
* CLI menu loops
* Input validation basics

---

## 🔮 Future Improvements (Optional)

* Search student by ID or name
* Grade statistics
* CSV export
* GUI version
* Input validation for grades
* Sorting students

---

## 👨‍💻 Author

Karan
Student Project – Python OOP Practice
