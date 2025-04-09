# -Priority-Based-Task-Scheduler-in-Python
A simple CLI-based task scheduler using a priority queue and deadline sorting. Add, remove, and manage your tasks with persistent storage in a .txt file.
# 🗂️ Task Scheduler in Python

This is a command-line-based **Task Scheduler** that helps you manage tasks based on **priority** and **deadline**. It uses a **priority queue (min-heap)** and supports persistent storage through a `.txt` file.

---

## ✨ Features

- ✅ Add new tasks with name, priority (1=High, 3=Low), and deadline (YYYY-MM-DD)
- ❌ Remove the highest-priority task
- 📋 Display tasks by priority
- 📅 Display tasks sorted by deadline
- 💾 Tasks are saved to and loaded from a file
- ✅ Input validations to ensure clean task entries

---

## 🔧 How It Works

- Tasks are stored in a **heap (priority queue)** based on the priority level.
- Sorting by deadline is done using **Insertion Sort** for educational purposes.
- All tasks are saved in a text file (`tasks.txt`) for persistence between runs.

---

## 🚀 Getting Started

### Requirements
- Python 3.x

### Clone the Repository

```bash
git clone https://github.com/your-username/task-scheduler-python.git
cd task-scheduler-python
Run the Program
bash
Copy
Edit
python task_scheduler.py
📁 File Structure
bash
Copy
Edit
task_scheduler.py      # Main script with Task and TaskScheduler classes
tasks.txt              # Stores your tasks persistently
📌 Sample Task Entry Format (in tasks.txt)
yaml
Copy
Edit
1, Learn DSA, 1, 2025-04-10
2, Do Homework, 3, 2025-04-15
🧠 Educational Use
This project is perfect for:

Beginners learning data structures (heap, sorting)

Practicing file I/O in Python

Building mini-projects with real-world logic


🙌 Contributions
Pull requests are welcome! If you find a bug or want to suggest a feature, feel free to open an issue.

👤 Author
Bereket Getaw Hailegebreal
🎓 Data Science Student
🌍 Ethiopia
📧 [bereketgetaw613@gmail.com]
