Daily Routine Web App
Description
Hi! It is a web application for managing daily tasks. You can create, track and manage your tasks using this application.

Project structure
The project consists of three main components: HTML markup, JavaScript logic (using several design patterns) and style rules using CSS.

HTML (index.html)
Structure: Defined sections for the header, main content, task form, task list and footer.
Scripts: The app script is connected.js responsible for the application logic.
Styles: The style.css style sheet is connected.
JavaScript (app.js )
Design Patterns:
Singleton Pattern: Used to create a single instance of TaskManager that manages tasks.
Observer Pattern: Implemented using TaskListObserver to track changes in tasks and update the list on the page.
Factory Method Pattern: TaskFactory creates task instances using a priority strategy.
Strategy Pattern: PriorityStrategy defines a priority strategy for tasks.
Decorator Pattern: DueDateDecorator and AttachmentDecorator add additional properties to tasks.
Modal View Control Pattern: TaskController controls a modal window for interacting with tasks.
MVC Pattern: Implemented via TaskController to control the modal window.
CSS (style.css)
Zeroing styles: Sets the basic styles for the page body.
Styles for sections: Styles are set for the title, main content, form, task list and footer.
Form Element Styles: Defined styles for the form, labels, text field, and button.
Footer styles: Set styles for the footer fixed at the bottom of the page.
How to use
Open the file index.html in a web browser.
In the "Create a Task" section, fill in the "Title" and "Description" fields and click the "Create Task" button to add a task.
The list of tasks will be displayed in the "Exercise List" section.
You can edit HTML, CSS and JavaScript files to customize the application to your needs.
Dependencies
Missing. The application is written using pure HTML, CSS and JavaScript.

Authors
Sanzhar
Bakhtiyar

License
This project is distributed under the MIT license - for details, see the LICENSE file
