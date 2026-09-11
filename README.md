# Note-Taking Website

A full-stack web application built with Python (Django framework) and Flask. The application allows users to create an account, securely log in, and manage individual notes on a simple web interface. This project was developed to practice full-stack web development concepts, including authentication, database management, Flask routing, and application organization using Blueprints and the application factory pattern.

## Features

User account registration
- User login and logout
- Password authentication
- Create personal notes
- Save notes in the database
- Delete notes
- Associate Notes with a personal account

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

## Run the project
1 - Ensure Python is installed on your computer
2 - Ensure Flask is installed for the project
```
TO INSTALL FLASK
- Run these commands:
       'python -m pip install flask' in PowerShell system
       'python -m pip install flask flask-sqlalchemy flask-login'
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

## User Interfaces of the Website

# Login Page
<img width="1009" height="647" alt="Screenshot 2026-09-09 093748" src="https://github.com/user-attachments/assets/69200b8c-895f-4ce3-bd1e-30a16f4292c5" />

# Sign-up Page
<img width="1010" height="612" alt="Screenshot 2026-09-09 093758" src="https://github.com/user-attachments/assets/f18e89de-ebcd-4764-b190-da910fa15220" />

# Main Website Interface
<img width="2190" height="1004" alt="image" src="https://github.com/user-attachments/assets/b22ad94f-aac6-4a78-b501-d8237185f82f" />

# Write and Save the Notes
<img width="1007" height="612" alt="Screenshot 2026-09-09 093908" src="https://github.com/user-attachments/assets/36f6a06c-36d4-43d9-aa22-7848e653a6b4" />
