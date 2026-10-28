# Task 1: To-Do List (Python)

## Description
A command-line to-do list written in Python. The user can add tasks and view them as a numbered list. Tasks are saved in a file called `tasks.json`, so they are still there the next time the program is run.

Built as **Task 1** of my Python Programming Internship at **DecodeLabs** (Batch 2026).

## Features
- Add tasks (empty tasks are rejected)
- View all saved tasks as a numbered list
- Tasks are saved automatically using JSON
- Invalid menu choices are handled without crashing
- Type `3` to exit

## How to Run
1. Install Python and Jupyter Notebook.
2. Download this repository (green **Code** button, then **Download ZIP**) and extract it.
3. Open a terminal in the extracted folder and start Jupyter:

```
jupyter notebook
```

4. Open `todo_list.ipynb`.
5. Click the code cell and press **Shift + Enter** to run it.
6. Follow the menu: type `1` to add a task, `2` to view tasks, `3` to exit.

## Example
```
--- TO-DO LIST ---
1. Add task
2. View tasks
3. Exit
Choose an option: 1
Enter a task: Finish Python assignment
Task added!

--- TO-DO LIST ---
1. Add task
2. View tasks
3. Exit
Choose an option: 2
1. Finish Python assignment

--- TO-DO LIST ---
1. Add task
2. View tasks
3. Exit
Choose an option: 3
Goodbye!
```

## Concepts Used
- Lists and `append()`
- Dictionaries (each task is a row with an `id` and a `task`)
- Loops and `if / elif / else`
- Functions (data logic separated from the user interface)
- Saving and Loading data with JSON
- `if __name__ == "__main__":` entry point

## Author
Shreya Metkar - [GitHub](https://github.com/shreyametkar6)
