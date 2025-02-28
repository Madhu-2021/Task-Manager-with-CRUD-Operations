# Task-Manager-with-CRUD-Operations

This is a simple Flask-based to-do list web application. It allows you to create, view, update, and delete tasks. The app uses an SQLite database to store task information.

## Features

- **Add tasks**: Create new tasks with a description.
- **View tasks**: See a list of all tasks, ordered by creation date.
- **Update tasks**: Edit the description of a task.
- **Delete tasks**: Remove a task from the list.

## Technologies Used

- **Flask**: Python web framework for building the app.
- **SQLAlchemy**: ORM (Object-Relational Mapping) for database operations.
- **SQLite**: Database for storing tasks.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- SQLAlchemy

You can install Flask and SQLAlchemy using pip:

```bash
pip install Flask SQLAlchemy
```

### Project Structure

```bash
app.py                # Main Flask app
templates/
    index.html        # HTML template for displaying tasks
    update.html       # HTML template for updating a task
test.db               # SQLite database (auto-generated)
```

### Running the Application

1. **Clone or download the repository**.
2. **Install dependencies**:
   ```bash
   pip install Flask SQLAlchemy
   ```
3. **Run the Flask app**:
   ```bash
   python app.py
   ```
4. Open your browser and navigate to `http://127.0.0.1:5000/` to use the app.

### Database Setup

The app uses an SQLite database (`test.db`) to store task information. The database is automatically created when you run the app for the first time.

## Routes

- **`/`**: Main page where tasks are displayed and can be added.
- **`/delete/<int:id>`**: Deletes a task with the given ID.
- **`/update/<int:id>`**: Updates a task with the given ID.

## Template Files

- **index.html**: The main page for displaying tasks and adding new tasks.
- **update.html**: The page for updating an existing task.

## License

This project is open-source and free to use.

## Author

Developed by Madhumitha M ☺️
