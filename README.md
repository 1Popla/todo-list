# Django Task Management Application


# Overview
This Django web application provides a simple yet effective task management system. It allows users to create, update, delete, and reorder tasks. Authentication is handled, ensuring that tasks are user-specific and secure.

# Features
- User authentication system
- Custom login
- User registration
# Task management
- Create, update, and delete tasks
- View task details
- Reorder tasks
# Usage
Run the Django development server: `python manage.py runserver`
1. Navigate to http://localhost:8000/ in your web browser to use the application.

# Application Structure
- CustomLoginView: Handles the login functionality.
- RegisterPage: Manages user registration.
- TaskList: Displays a list of tasks for the logged-in user.
- TaskDetail: Shows details of a specific task.
- TaskCreate: Provides a form to create a new task.
- TaskUpdate: Allows updating an existing task.
- TaskDelete: Enables deletion of a task.
- TaskReorder: Implements functionality to reorder tasks.
