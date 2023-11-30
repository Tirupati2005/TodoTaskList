# TodoTaskList

Task Details: 

Creating a Django task that involves creating a user, showing a to-do list for that user, and performing CRUD (Create, Read, Update, Delete) operations is a great way to evaluate a candidate's understanding of Django's basic concepts. Here's a sample task description you can use:

Task: Django To-Do List Application

Objective:
Create a simple Django application that allows users to manage their to-do lists. Users should be able to register, log in, create, view, update, and delete tasks in their to-do lists.

Requirements:

1. User Registration and Authentication:
   - Users should be able to register with a username and password.
   - Users should be able to log in and log out.

2. To-Do List Management:
   - Once logged in, users should see a dashboard displaying their to-do list tasks.
   - Users should be able to create new tasks, specifying a task name and description.
   - Users should be able to view a list of their tasks.
   - Users should be able to update the name and description of a task.
   - Users should be able to mark a task as completed.
   - Users should be able to delete a task.

3. User Profile:
   - Users should have a profile page displaying their username and a list of their tasks.

4. Security and Validation:
   - Implement user authentication and authorization to ensure that users can only manage their tasks.
   - Implement appropriate form validation to handle errors gracefully.

5. User-Friendly Interface:
   - Design a user-friendly and responsive web interface.

6. Bonus (Optional):
   - Implement task categories or priorities.
   - Add due dates for tasks.
   - Implement search or filter functionality for tasks.

Guidelines:

- Use Django's built-in authentication system for user registration and login.
- Use Django models to define the necessary data structures (e.g., User, Task).
- Create Django views and templates for rendering user interfaces.
- Use Django forms for handling user input.
- Organize your code following Django best practices, including URL routing and project   structure.
- Use a version control system like Git to manage your codebase.

Evaluation Criteria:

Candidates will be evaluated based on their ability to:
- Implement user registration and authentication.
- Create Django models, views, and templates.
- Implement CRUD operations for tasks.
- Handle form validation and user input.
- Design a user-friendly interface.


**Create a Django Project and App:-**

--->Create a Django project
django-admin startproject todo_list

--->Create a Django app within the project
cd todo_list
python manage.py startapp base
- Ensure data security and user authorization.

**Define Models:-**

In your base/models.py file, define the models for users and tasks:
