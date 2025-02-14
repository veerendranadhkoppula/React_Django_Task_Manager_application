# Django-React Task Manager

This is a Task Manager application built with Django (backend) and React (frontend).

## Prerequisites

- Python (version 3.6+)
- Node.js (version 12+)
- npm (Node Package Manager)

## Backend Setup (Django)

1. **Navigate to the backend directory:**

    ```bash
    cd backend
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply database migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Create a superuser (optional):**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the Django development server:**

    ```bash
    python manage.py runserver
    ```

## Frontend Setup (React)

1. **Navigate to the frontend directory:**

    ```bash
    cd ../frontend  # Adjust the path as needed
    ```

2. **Install required Node.js packages:**

    ```bash
    npm install
    ```

3. **Start the React development server:**

    ```bash
    npm start
    ```

## Access the Application

- **Backend (Django):** Open your web browser and go to `http://localhost:8000`
- **Frontend (React):** Open your web browser and go to `http://localhost:3000`
- **Django Admin Panel (if superuser created):** Open your web browser and go to `http://localhost:8000/admin`

## Additional Information

- Make sure your virtual environment is activated when working with the Django backend.
- If you encounter any issues, please check the project's documentation or open an issue on GitHub.
