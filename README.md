To-Do List Application in Python
======================

This is a simple To-Do List application written in Python. It allows users to add tasks, view tasks, edit tasks, mark tasks as completed, delete tasks, and save tasks to a text file.


Functions
---------

1. `print_banner`: Prints the ASCII art banner for the application.

2. `display_menu`: Displays the menu options for the user to choose from.

3. `add_task(tasks)`: Adds a task to the list of tasks.

4. `view_tasks(tasks)`: Displays all tasks along with their status (completed/pending).

5. `edit_task(tasks)`: Allows the user to edit a specific task.

6. `mark_completed(tasks)`: Marks a task as completed.

7. `delete_task(tasks)`: Deletes a task from the list.

8. `save_tasks(tasks)`: Saves the tasks to a text file in the current directory. The user provides the filename.

9. `exit_program(_)`: Exits the program.


Main Functionality
------------------

The `main` function initializes an empty list of tasks and displays the main menu. It then enters a loop where it repeatedly prompts the user for input and executes the corresponding function based on the user's choice. The loop continues until the user chooses to exit the program.


Usage
-----

1. Run the Jupyter Notebook file containing the python script named `todo_list.jpynb`.
2. Follow the on-screen instructions to perform various tasks:
   - Add a task: Enter option 1 and provide the task description.
   - View tasks: Enter option 2 to see all the tasks along with their status (Completed/Pending).
   - Edit a task: Enter option 3 and follow the prompts to select and edit a task.
   - Mark a task as completed: Enter option 4 and select a task to mark it as completed.
   - Delete a task: Enter option 5 and select a task to delete it from the list.
   - Save tasks to a file: Enter option 6 and provide the file name to save the tasks in TXT format.
   - Exit the application: Enter option 7 to exit the application.

Please note that the application automatically saves tasks to a TXT file named by you in the current directory when you choose the "Save Tasks to File" option.

Authors: Eren Celik, Samu Elinger, Katrin Alexandrova Tosheva
