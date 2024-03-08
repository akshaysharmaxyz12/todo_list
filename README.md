# ToDo List Project

This project implements a ToDo list application using Python Flask for backend development and HTML, CSS, and JavaScript for frontend.

## Features

- **Add Tasks:** Users can add new tasks with a title, description, start date, start time, end date, and end time.
- **View Tasks:** Tasks are displayed based on their status (pending, processing, completed).
- **Edit Tasks:** Users can edit task details such as title, description, start date, start time, end date, and end time.
- **Delete Tasks:** Tasks can be deleted individually.
- **Drag and Drop:** Tasks can be moved between different statuses by dragging and dropping them into the corresponding section.

## Backend

The backend is developed using Python Flask and interacts with a MariaDB database for data storage. The main file for the backend is `server.py`.

### Dependencies

- Flask: Micro web framework for Python.
- mysql-connector: Connector for MySQL databases.
- Flask-CORS: Extension for handling Cross-Origin Resource Sharing (CORS) in Flask applications.

### Installation

1. Install Python and Flask.
2. Install MySQL and create a database named `todo_list_db`.
3. Update database connection details in `server.py`.
4. Install required Python packages using `pip install flask flask-cors mysql-connector-python`.

### Running the Backend

Run `server.py` using Python:

```bash
python server.py


Frontend
The frontend is implemented using HTML, CSS, and JavaScript. The main files for the frontend are index.html and todoForm.html. JavaScript is used for adding interactivity to the application.

Dependencies
No external dependencies are required for the frontend.

Running the Frontend
Open index.html or todoForm.html in a web browser.

Usage
Open the application in a web browser.
Add tasks using the "Add Todo" button on the homepage (index.html) or the task form page (todoForm.html).
Drag and drop tasks between different sections to update their status.
Edit or delete tasks as needed.


You can copy this content and save it as `README.md` in your project directory. This Markdown file will provide a clear overview of your ToDo List project.
