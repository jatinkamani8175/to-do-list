📋 To-Do List Application (Command-Line Based)
This is a simple command-line To-Do List manager written in Python. It allows you to view, add, and remove tasks, with the data persisted to a local text file.

📁 Files
todolist.py — Main Python script that runs the application.

todo.txt — Text file where tasks are saved automatically.

🚀 Features
View your current to-do list.

Add new tasks.

Remove completed/unwanted tasks.

Automatically saves tasks between sessions.

🛠️ How to Run
Make sure Python is installed (Python 3+ recommended).

Open a terminal/command prompt.

Run the script:

bash
Copy
Edit
python todolist.py
Choose an option from the menu:

1: View tasks

2: Add a task

3: Remove a task

4: Exit and save tasks

💾 Persistent Storage
Tasks are saved to todo.txt in the same directory as the script. If the file does not exist, it will be created automatically when tasks are saved.

🧪 Example
bash
Copy
Edit
Choose an option:
1. View Tasks
2. Add Task
3. Remove Task
4. Exit
Enter your choice (1-4): 2
Enter a new task: Submit project report
Task added: 'Submit project report'

📌 Notes
Input validation is included to prevent crashes on invalid input.

Empty tasks are not added.

