## Level 1 – Task 1: CLI Task Manager

### Objective

To build a Command Line Interface (CLI) based Task Manager application using Python that allows users to manage daily tasks efficiently.

### Description

In this task, a CLI-based Task Manager application was developed using Python. The application allows users to perform basic task management operations such as adding new tasks, listing existing tasks, marking tasks as completed, and deleting tasks. All task data is stored locally using a JSON file to ensure persistence between program executions.

### Tasks Performed

* Created a command-line based application
* Implemented task addition functionality
* Displayed all stored tasks using list command
* Marked tasks as completed using task ID
* Deleted tasks from the task list
* Stored task data in a local JSON file
* Loaded saved tasks automatically during program startup

### Tools Used

* Python
* JSON
* Command Line Interface (CLI)
* VS Code

### Task Fields

Each task includes the following fields:

* **id** – Unique identifier for each task
* **title** – Task name
* **description** – Optional task details
* **created_at** – Task creation timestamp
* **completed** – Completion status of the task

### Result

The CLI Task Manager application successfully performs add, list, complete, and delete operations. Tasks are permanently stored in a JSON file and can be accessed even after restarting the application.
# cli-task-manage
Command Line Task Manager built using Python
