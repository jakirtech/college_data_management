# college_data_management
# 🎓 School Management System (Python)

A simple **School Management System** built with Python using **Object-Oriented Programming (OOP)** principles and **JSON** for persistent data storage. This project allows users to register students and teachers, assign grades to students, and view stored information.

## 🚀 Features

* 👨‍🎓 Register new students
* 👨‍🏫 Register new teachers
* 📚 Add grades for students
* 📊 Calculate and display student average marks
* 📋 View student details
* 📋 View teacher details
* 💾 Store data permanently using a JSON file
* ✅ Basic email validation
* 🔒 Prevent duplicate Student Roll Numbers and Teacher Employee IDs
* 🏗️ Demonstrates Abstraction using Python's `ABC` module

---

## 🛠️ Technologies Used

* Python 3
* JSON
* Object-Oriented Programming (OOP)
* Abstract Base Classes (`abc`)
* Pathlib

---

## 📂 Project Structure

```text
School-Management-System/
│
├── main.py               # Main Python program
├── school_data.json      # Stores student and teacher records
└── README.md             # Project documentation
```

---

## 📌 Functionalities

### Student

* Register a new student
* Store:

  * Name
  * Age
  * Email
  * Roll Number
* Add subject-wise grades
* View student details
* Calculate average marks automatically

### Teacher

* Register a new teacher
* Store:

  * Name
  * Age
  * Email
  * Subject
  * Employee ID
* View teacher details

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/School-Management-System.git
```

2. Navigate to the project folder

```bash
cd School-Management-System
```

3. Run the program

```bash
python main.py
```

---

## 📖 Menu

```text
1. Register Student
2. Register Teacher
3. Add Grades
4. Show Student Details
5. Show Teacher Details
```

---

## 💾 Data Storage

All records are saved inside:

```text
school_data.json
```

The data is automatically loaded when the program starts and saved after every update.

---

## 🏛️ OOP Concepts Used

* Classes & Objects
* Inheritance
* Abstraction
* Method Overriding
* Static Methods

---

## 📸 Sample Output

```text
press 1 to register a student
press 2 to register a teacher
press 3 to add grades
press 4 to show a student detail
press 5 to show a teacher detail

please tell your choice :- 1
```

---

## 🔮 Future Improvements

* Delete student/teacher records
* Update existing information
* Search students by name
* Better email validation using Regular Expressions
* Password-based login system
* Command-line interface improvements
* Database integration (SQLite/MySQL)
* Graphical User Interface (Tkinter/PyQt)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**Jakir Hossain**

If you found this project helpful, don't forget to ⭐ star the repository!
