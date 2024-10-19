# To-Do List API

This is a simple To-Do List API built with Django and Django REST Framework. The API allows you to create, retrieve, update, and delete tasks.

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   cd <your-project-directory>
2. Download the 

python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate

3.Install dependencies:
pip install -r requirements.txt

4.Run migrations:
python manage.py migrate

5.Run the server:
python manage.py runserver



API Endpoints
GET /api/tasks/ - Retrieve all tasks.
POST /api/tasks/ - Create a new task.
GET /api/tasks/{id}/ - Retrieve a task by ID.
PUT /api/tasks/{id}/ - Update a task by ID.
DELETE /api/tasks/{id}/ - Delete a task by ID.
