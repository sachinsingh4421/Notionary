# 📝 Notionary

A modern, responsive web application for managing your personal notes. Built with Flask and Bootstrap 5, this app allows you to create, view, and delete notes with a clean and intuitive interface.

![Notionary Screenshot](https://images.pexels.com/photos/261651/pexels-photo-261651.jpeg?auto=compress&cs=tinysrgb&w=200)

## ✨ Features

- 🔐 User authentication (Sign up, Login, Logout)
- 📝 Create and manage notes
- 🎨 Clean, responsive design
- 🔄 Real-time updates
- 📱 Mobile-friendly interface
- 🔒 Secure password hashing

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sachinsingh4421/Notionary.git
   cd Notionary
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**
   ```bash
   python
   >>> from website import create_app, db
   >>> app = create_app()
   >>> with app.app_context():
   ...     db.create_all()
   ```

5. **Run the application**
   ```bash
   python main.py
   ```

6. **Open in your browser**
   Visit `http://127.0.0.1:5000`

## 🛠️ Built With

- [Flask](https://flask.palletsprojects.com/) - The web framework used
- [SQLAlchemy](https://www.sqlalchemy.org/) - Database ORM
- [Bootstrap 5](https://getbootstrap.com/) - Frontend framework
- [Flask-Login](https://flask-login.readthedocs.io/) - User session management
- [Werkzeug](https://werkzeug.palletsprojects.com/) - Security and password hashing
