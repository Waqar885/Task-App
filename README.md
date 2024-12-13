
# To-Do List Application

A simple yet functional to-do list application built using Flask and SQLAlchemy. This app allows users to add, update, view, and delete tasks with ease. It also includes a clean and responsive interface using Bootstrap.

## Features

- Add new tasks with titles and descriptions.
- View a list of all tasks along with their creation time.
- Update existing tasks.
- Delete tasks from the list.
- Interactive and responsive design for an enhanced user experience.

## Technologies Used

- **Python** (Flask Framework)
- **HTML** (with Jinja2 templating)
- **CSS** (Bootstrap and custom styles)
- **SQLite** (via SQLAlchemy ORM)
- **Bootstrap** for responsive design

## File Structure

```
todo-app/
|-- app.py                # Main Flask application
|-- templates/
|   |-- base.html         # Base template
|   |-- index.html        # Main page for task management
|   |-- update.html       # Page for updating tasks
|-- static/
|   |-- styles.css        # Custom CSS file
```

## How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-app.git
   cd todo-app
   ```
2. Install dependencies:

   ```bash
   pip install flask flask-sqlalchemy
   ```
3. Set up the database:

   ```bash
   python
   >>> from app import db
   >>> db.create_all()
   >>> exit()
   ```
4. Run the application:

   ```bash
   python app.py
   ```
5. Open a web browser and go to `http://127.0.0.1:8000` to access the app.

## Usage

### Adding Tasks

- Navigate to the home page.
- Fill out the task title and description fields.
- Click "Submit" to add the task to the list.

### Viewing Tasks

- The tasks table displays all tasks with their respective details such as title, description, and creation time.

### Updating Tasks

- Click the "Update" button for the task you want to modify.
- Edit the fields and click "Update" to save changes.

### Deleting Tasks

- Click the "Delete" button for the task you want to remove.

## Screenshots

*Include screenshots of the application to showcase the features.*

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests for improvements or new features.

---

Built with ❤️ by Waqar Raza using Flask.
