# Product Management System

A Django-based CRUD application for managing products with SQLite database.

## Features

- Create, Read, Update, Delete (CRUD) products
- View all products in a table format
- SQLite database for persistent storage
- Simple and clean HTML interface
- Form validation
- Responsive design
- Admin panel for management

## Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

### Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Raghavendracharykurella/product-management-system.git
   cd product-management-system
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Open http://127.0.0.1:8000/

## Technologies Used

- Backend: Python 3.x, Django 4.2.7
- Database: SQLite3
- Frontend: HTML5, CSS3
- Tools: Git, GitHub

## License

MIT License
