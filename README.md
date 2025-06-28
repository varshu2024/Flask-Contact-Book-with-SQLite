# Flask-Contact-Book-with-SQLite

```markdown
# Flask Contact Book with SQLite

![Flask Contact Book Screenshot](screenshot.png) <!-- Replace with your actual screenshot -->

A simple web-based contact management application built with Flask and SQLite, demonstrating CRUD operations with Flask-SQLAlchemy.

## Features

- **Create, Read, Update, Delete** contacts
- Responsive web interface with Bootstrap
- SQLite database with SQLAlchemy ORM
- Flash messages for user feedback
- Form validation



## Technologies Used 

- Python 3
- Flask
- Flask-SQLAlchemy
- SQLite
- Bootstrap 5
- HTML5
- Jinja2 templating

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flask-contact-book.git
   cd flask-contact-book
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python app.py
   ```

5. **Access the application**:
   Open your browser and navigate to `http://localhost:5000`

## Database Setup

The application will automatically create an SQLite database file (`instance/contacts.db`) when you first run it.

## Project Structure

```
flask-contact-book/
├── app.py                # Main application file
├── models.py             # Database models
├── requirements.txt      # Dependencies
├── instance/             # Database location
│   └── contacts.db
├── templates/            # HTML templates
│   ├── base.html         # Base template
│   ├── index.html        # Contact list
│   ├── add.html          # Add contact form
│   ├── edit.html         # Edit contact form
│   └── view.html         # View single contact
└── static/               # Static files (CSS, JS, images)
    └── screenshots/      # Application screenshots
```

## Usage

1. **View all contacts**: The homepage shows all contacts in the database
2. **Add a contact**: Click "Add New Contact" button
3. **View details**: Click "View" on any contact
4. **Edit contact**: Click "Edit" on any contact
5. **Delete contact**: Click "Delete" on any contact (with confirmation)

## Learning Objectives

This project demonstrates:
- Flask web application development
- SQLite database integration
- ORM usage with Flask-SQLAlchemy
- CRUD operations implementation
- Form handling and validation
- Template inheritance with Jinja2

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
