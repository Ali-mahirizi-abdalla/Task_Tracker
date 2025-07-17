# Task Tracker Web Application

## Project Owner
**Ali Mahirizi Abdalla**  
Student, Pwani University TVET

---

## Project Overview

This project is a beginner-friendly **Task Tracker Web Application**. The goal is to help users manage their daily tasks by allowing them to add, edit, delete, and mark tasks as complete. This project is ideal for learning the basics of full-stack software engineering using Python (Flask) for the backend and HTML/CSS/JavaScript for the frontend.

---

## Features

- Add new tasks
- View all tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Persist tasks in a database

---

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Database:** SQLite
- **Version Control:** Git & GitHub

---

## System Architecture

```
[Browser] <-- HTML/CSS/JS --> [Flask Backend (Python)] <-- SQLite Database -->
```

---

## Project Structure

```
task-tracker/
├── README.md
├── app.py                # Flask backend
├── requirements.txt      # Python dependencies
├── templates/
│   └── index.html        # Main UI
├── static/
│   └── style.css         # Styling
├── instance/
│   └── tasks.db          # SQLite DB
```

---

## UI Sketch

```
---------------------------------
|       Task Tracker            |
---------------------------------
|  [Add New Task] [Input Field] |
|                               |
|  Tasks:                       |
|  ---------------------------  |
|  [ ] Buy groceries   [Edit] [Delete]   |
|  [x] Finish homework [Edit] [Delete]   |
|  [ ] Clean room      [Edit] [Delete]   |
|                               |
|  Completed Tasks:             |
|  [x] Finish homework          |
---------------------------------
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/task-tracker.git
cd task-tracker
```

### 2. Set Up Python Environment

Install required packages using `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app.py
```

### 4. Open in Browser

Visit `http://localhost:5000` to use the app.

---

## Future Improvements

- User authentication (sign up/login)
- Task categories or priorities
- Task deadlines and reminders
- Responsive mobile UI

---

## License

This project is for educational purposes at Pwani University TVET.