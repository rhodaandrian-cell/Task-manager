# Task Management System

This project is a simple Python-based Task Management System. It allows users to add tasks, mark tasks as complete, view pending tasks, and track overall progress.

## Project Structure

Task-manager/
├── main.py
└── task_manager/
    ├── __init__.py
    ├── task_utils.py
    └── validation.py

## Features

- Add a new task
- Mark a task as complete
- View pending tasks
- View task completion progress
- Validate task title, description, and due date

## Requirements

- Python 3.x

## How to Run

1. Open the project folder in VS Code or terminal.
2. Make sure your folder structure matches the project structure above.
3. Run the program:

python main.py

If `python` does not work on your system, try:

python3 main.py

## Menu Options

When the program runs, you will see this menu:

1. Add Task
2. Mark Task as Complete
3. View Pending Tasks
4. View Progress
5. Exit

## Validation Rules

- Task title cannot be empty
- Task description cannot be empty
- Due date must be in `YYYY-MM-DD` format

## Example Task Format

Each task is stored as a dictionary like this:

task = {
    "title": "Groceries",
    "description": "Shop at Market Basket for food",
    "due_date": "2024-06-26",
    "completed": False
}

## Example Usage

- Add a task by entering a title, description, and due date
- View pending tasks to see incomplete tasks
- Mark a task as complete by selecting its number
- View progress to see the percentage of completed tasks

## Files Description

### main.py
Contains the main menu-driven program for user interaction.

### task_manager/task_utils.py
Contains functions for:
- adding tasks
- marking tasks as complete
- viewing pending tasks
- calculating progress

### task_manager/validation.py
Contains functions for validating:
- task title
- task description
- due date

## Author

Rhoda