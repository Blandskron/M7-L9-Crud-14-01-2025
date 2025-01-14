# Links Management Project

This project is a simple Django web application for managing links. It provides functionalities to create, view, update, and delete links. The application is styled using Bootstrap 4 for a modern and responsive user interface.

## Features

- **Add New Link:** Create new links with a URL and description.
- **Edit Existing Links:** Update the URL or description of a link.
- **Delete Links:** Remove unwanted links with a confirmation prompt.
- **View Links:** List all saved links with options to edit or delete them.

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd links-management-project
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Start the development server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the application:**
   Open your browser and navigate to `http://127.0.0.1:8000/`.

## File Structure

- **`base.html`:** The base template that includes the Bootstrap 4 styles and JavaScript files.
- **Templates for CRUD operations:**
  - `delete_link.html`: Confirmation page for deleting a link.
  - `form.html`: Used for creating and editing links.
  - `link_list.html`: Displays a list of all links with options to edit or delete.
- **Static Files:**
  Bootstrap is integrated using `django-bootstrap4` for dynamic inclusion of styles.

## Styling

The project uses Bootstrap 4 for:
- Responsive layouts.
- Styled buttons, forms, and list groups.
- Alerts for user interactions.

## How to Use

1. Navigate to the homepage to see a list of links.
2. Click on "Add New Link" to create a new link.
3. Use the "Edit" button to modify an existing link.
4. Click "Delete" to remove a link (a confirmation prompt will appear).

## Requirements

- Python 3.6+
- Django 3.2+
- django-bootstrap4

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

