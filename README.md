<h1>TASK 1</h1>
<h3>Enhanced CLI Calculator 🧮</h3>
<br>
A small, safe, and user-friendly command-line calculator written in Python.
<br>
<b>Features</b>
Basic operations: add, subtract, multiply, divide
Extras: power, square root, percent
Free-form expressions (safe AST-based evaluation)
ans token → reuse last result
Shows and saves calculation history
<br>
<b>Follow the menu options:<b/>
1-7 → basic operations
<br>
8 → enter an expression (2+3*4, ans/2, etc.)
<br>
9 → show history
<br>
S → save history to file
<br>
Q → quit

<h1> TASK2 </h1>
<h3>Weekly To-Do List Manager</h3>

A simple <b>console-based Python application</b> to manage your weekly to-do tasks.  
You can add multiple tasks per day, mark them as done, edit, remove, or clear all tasks at once. Tasks are stored persistently in a text file (`tasks.txt`) in the same folder.

<b>Features</b>
- Add tasks for each day of the week (Monday → Sunday)  
- View tasks day-wise with status symbols:
  - ⏳ Pending  
  - 👍 Done  
- Mark a single task as done  
- Edit a task  
- Remove a single task  
- Remove all tasks at once
- Mark all tasks as done 
- Tasks are saved in `tasks.txt` in the same folder, so they persist across sessions

  Follow the on-screen menu to:
1. View tasks
2. Add tasks
3. Mark tasks as done
4. Remove tasks
5. Edit tasks
6. Remove all tasks
7. Mark all tasks as done
8. Exit

<b>File Structure</b>
<br>
task2/
│
<br>
├─ todo.py        # Main Python script
<br>
├─ tasks.txt      # Stores your weekly tasks (auto-created)
<br>
└─ README.md      # Project documentation


