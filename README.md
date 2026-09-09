# Note-Taking Website

A full-stack web application built with Python (Django framework) and Flask. The application allows users to create an account, securely log in, and manage individual notes on a simple web interface. This project was developed to practice full-stack web development concepts, including authentication, database management, Flask routing, and application organization using Blueprints and the application factory pattern.

## Features

User account registration
- User login and logout
- Password authentication
- Create personal notes
- Save notes in the database
- Delete notes
- Associate Notes with a personal account.

## Technologies

| Backend          | Database | Frontend   |
|------------------|----------|------------|
| Python           | SQLite   | CSS
| Flask            |          | HTML
| Flask-SQLAlchemy |          | Bootstrap  |
| Flask-Login      |          | JavaScript |

## Project Structure
```
Note_taking_website/
│
├── website/
│     ├── __init__.py
│     ├── auth.py
│     ├── models.py
│     ├── views.py
│     │
│     ├── templates/
│     │     ├── base.html
│     │     ├── home.html
│     │     ├── login.html
│     │     └── sign_up.html
│     │
│     └── static/
│
├── main.py
├── requirements.txt
└── README.md
```
