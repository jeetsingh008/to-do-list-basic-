
To-Do List Web Application
This is a simple and elegant to-do list web application that allows users to add, edit, delete, and mark tasks as complete. It includes icons for user interaction, making the application intuitive and easy to use.

Setup Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/todo-list-app.git
cd todo-list-app
Open the Project

Open the project folder in your favorite code editor (e.g., Visual Studio Code).
Run the Application

Simply open the index.html file in your browser.
Component Descriptions
HTML Structure
<div class="container">: Main container for the to-do list application.
<h1>: Title of the application.
<div class="task-input">: Container for the input field and add button.
<input id="new-task">: Input field for entering new tasks.
<button id="add-task">: Button to add a new task.
<ul id="task-list">: List where tasks are displayed.
CSS Styles
General Styles: Basic styling for the application layout, including body and container.
Input and Button Styles: Styling for the input field and buttons to ensure a consistent look and feel.
Task List Styles: Styling for the task list items, including spacing, borders, and icons.
JavaScript Functionality
Event Listeners: Listeners for adding tasks and button actions (edit, delete, complete).
Functions:
addTask(taskText): Adds a new task to the list.
editTask(taskItem, taskSpan): Edits the text of an existing task.
deleteTask(taskItem): Deletes a task from the list.
completeTask(taskSpan): Toggles the completed state of a task.
How to Use the Application
Adding a Task
Enter a Task: Type your task in the input field at the top of the application.
Add the Task: Click the "Add" button or press Enter to add the task to the list.
Editing a Task
Edit Icon: Click the edit icon (pencil) next to the task you want to edit.
Update Task: A prompt will appear. Enter the new task text and press OK to save changes.
Deleting a Task
Delete Icon: Click the delete icon (trash can) next to the task you want to remove.
Confirm Deletion: The task will be immediately removed from the list.
Marking a Task as Complete
Complete Icon: Click the complete icon (check) next to the task you want to mark as completed.
Toggle Complete: The task text will be struck through to indicate completion. Click again to unmark.
Full Code
Here is the complete code for the application, including HTML, CSS, and JavaScript: