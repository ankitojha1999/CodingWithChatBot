# Task Management App
## Youtube video Link for webApp voiceover - https://youtu.be/-noWn9YJAkc
## Overview
This is a task management application built using Python and Flask. It allows users to register, log in, and manage their tasks. The application supports CRUD operations for tasks, user authentication, task categorization, priority setting, due date tracking, and search functionality.


## Features
- **User Authentication and Authorization**: Users can register, log in, and log out.
- **CRUD Operations for Tasks**: Users can create, read, update, and delete tasks.
- **Task Categorization and Priority Setting**: Tasks can be categorized and assigned a priority.
- **Due Date Tracking and Reminders**: Tasks have due dates, and reminders can be set.
- **Search and Filter Functionality**: Users can search and filter tasks.

## Setup Instructions

### Prerequisites
- Python 3.x
- Flask
- Werkzeug

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/ankitojha1999/CodingWithChatBot.git
    cd task_management_app
    ```

2. Install the required packages:
    ```sh
    pip install flask werkzeug
    ```

3. Initialize the database:
    ```sh
    python -c 'from app import init_db; init_db()'
    ```

### Running the Application
1. Set the `FLASK_APP` environment variable:
    ```sh
    export FLASK_APP=app.py
    ```

2. Run the application:
    ```sh
    flask run
    ```

3. Open your browser and go to `http://127.0.0.1:5000/`.

### Running Tests
1. Run the unit tests:
    ```sh
    python -m unittest tests.py
    ```

## File Descriptions

### app.py
This is the main application file that contains the Flask routes and the core logic for the application.

### utils.py
This file contains utility functions for database connection and password hashing/checking.

### tests.py
This file contains unit tests for the main functions of the application.

### templates/
This directory contains HTML templates for the frontend interface, including templates for index, login, register, add task, edit task, and task details.

### static/
This directory contains static files such as CSS for styling the application.

### schema.sql
This file contains the SQL schema for initializing the database.

