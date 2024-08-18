# Full-Stack To-Do List Application

This is a full-stack To-Do List application built with a Django backend and a frontend using HTML, CSS, and JavaScript. The project allows users to register, log in, and manage their to-do lists.

## Project Structure

### Backend

- **Framework:** Django
- **Purpose:** Provides REST API endpoints for user authentication, to-do list management, and CRUD operations.
- **Key Files:**
  - `settings.py`: Contains Django project settings.
  - `urls.py`: URL routing for the Django application.
  - `views.py`: Handles the logic for the application.
  - `models.py`: Defines the data models for the application (e.g., User, ToDo).
  - `serializers.py`: Serializes and deserializes data for API endpoints.

### Frontend

- **Technologies:** HTML, CSS, JavaScript
- **Purpose:** Provides the user interface for interacting with the to-do list application.
- **Key Files:**
  - `register.html`: User registration page.
  - `login.html`: User login page.
  - `todo.html`: Main to-do list page where users can view, add, update, and delete tasks.
  - `todo.css`: CSS styles for the to-do list page.
  - `styles.css`: General styles for the project.
  - `index.js`: JavaScript file to handle frontend logic and API calls.

## How to Run the Project Locally

### Prerequisites

- Python 3.x installed
- Node.js and npm installed

### Backend Setup

1. **Clone the repository:**
   ```bash
    git clone <repository-url>
    cd backend/todo_api
    ```

2. **Create a virtual environment:**
   ```bash
    python -m venv env
    ```

3. **Activate the virtual environment:**
   - On Windows:
     ```bash
     env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```
     
4. **Install the required packages:**
   ```bash
    pip install -r requirements.txt
    ```

5. **Apply migrations:**
   ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Run the development server:**
   ```bash
    python manage.py runserver
    ```
- **The backend server will be running at http://127.0.0.1:8000/.**
  

### Frontend Setup

1. **Navigate to the frontend directory:**
   ```bash
    cd ../frontend
    ```

2. **Serve the frontend files:**
   ```bash
    npx serve .
    ```

## Features:
  - **User Registration:** Users can create an account.
  - **User Login:** Users can log in with their credentials.
  - **To-Do List Management:**
    -  View existing tasks.
    - Add new tasks.
    - Edit existing tasks.
    - Delete tasks.

## Project Structure:
  ```plaintext
  project-root/
    │
    ├── backend/todo_api/
    │   ├── manage.py
    │   ├── todo_api/
    │   │   ├── settings.py
    │   │   ├── urls.py
    │   │   ├── wsgi.py
    │   │   └── ...
    │   └── todo/
    │       ├── models.py
    │       ├── views.py
    │       ├── serializers.py
    │       └── ...
    │
    ├── frontend/
    │   ├── index.js
    │   ├── register.html
    │   ├── login.html
    │   ├── todo.html
    │   ├── todo.css
    │   └── styles.css
    │
    └── README.md
  ```

        
