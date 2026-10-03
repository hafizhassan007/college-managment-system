# 🎓 College Management System — GICCL

A simple, elegant records manager for students, teachers, and grades — built with **Python** and **Streamlit**, for **Govt. Islamia Graduate College, Civil Lines, Lahore**.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

- 📝 **Register** students and teachers with validated details (name, age, email, roll number / employee ID)
- 📊 **Add, update, and delete grades** per subject for any student
- 🔎 **Look up** individual student or teacher records instantly
- ✏️ **Full CRUD** — create, read, update, and delete both student and teacher records from dedicated "Manage" pages
- 🏠 **Dashboard** with live counts and a summary table of all students (with average grade) and teachers
- 💾 **Persistent storage** — all data is saved locally to `school_Data.json`, no external database required
- 🎨 **Custom brown & cream theme** with the college crest in the sidebar and header
- ✅ **Duplicate & email validation** to keep records clean

## 🖥️ Screenshots

*(Add a screenshot of the dashboard and the registration form here once you have the app running.)*

## 📦 Requirements

- Python 3.9+
- [Streamlit](https://streamlit.io/)
- [Pillow](https://pypi.org/project/Pillow/) (for the logo/page icon)

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/college-management-system.git
   cd college-management-system
   ```

2. **(Recommended) Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate      # on Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install streamlit pillow
   ```

4. **Run the app**
   ```bash
   streamlit run app.py
   ```

5. Open the URL shown in the terminal (usually `http://localhost:8501`) in your browser.

> **Note:** Run the command from the same folder as `app.py`, so `school_Data.json` is created/read in the right place and your data persists between sessions.

## 🗂️ Project Structure

```
college-management-system/
├── app.py              # Main Streamlit application
├── school_Data.json    # Auto-created on first run — stores all records
└── README.md
```

## 🧭 Usage

| Page                  | What it does                                              |
|------------------------|-------------------------------------------------------------|
| 🏠 Dashboard           | Overview of all students and teachers                      |
| 📝 Register Student    | Add a new student record                                   |
| 🍎 Register Teacher    | Add a new teacher record                                   |
| 📊 Add Grades          | Record a grade for a student's subject                     |
| 🔎 Student Details     | Search a student by roll number                             |
| 🔎 Teacher Details     | Search a teacher by employee ID                             |
| ✏️ Manage Students     | Edit or delete a student, and edit/delete their grades      |
| ✏️ Manage Teachers     | Edit or delete a teacher                                    |

## 🛠️ Tech Stack

- **Frontend/App:** Streamlit
- **Language:** Python
- **Storage:** JSON file (`school_Data.json`)
- **Design pattern:** Simple OOP model (`Person` abstract base class → `Student`, `Teacher`)

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for bug fixes, new features, or UI improvements.

## 📄 License

This project is licensed under the MIT License — feel free to use and modify it for your own institution.

---

Built with ❤️ for **Govt. Islamia Graduate College, Civil Lines, Lahore** (Since 1958).
