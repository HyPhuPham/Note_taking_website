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
|          └── index.js
│
└── main.py

```

### Run the project
1 - Ensure Python is installed on your computer
2 - Ensure Flask is installed for the project
```
TO INSTALL FLASK
- Run: 'python -m pip install flask' in PowerShell system
- Also run: 'python -m pip install flask flask-sqlalchemy flask-login'
```
3 - Locate and run the file named main.py 
4 - In the terminal, there is a list of code lines as presented
```
Created Database!
 * Serving Flask app 'website'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
 * Restarting with stat
Created Database!
 * Debugger is active!
 * Debugger PIN: 564-499-321
```
The link http://127.0.0.1:5000 is the portal to connect to the website

