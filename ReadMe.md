# Secure Login System

## Project Overview

The Secure Login System is a web-based authentication application developed using Python Flask and SQLite. The purpose of this project is to provide a secure user registration and login mechanism by implementing password hashing, SQL injection protection, session management, and secure logout functionality.

## Objectives

* To create a secure user registration system.
* To authenticate users using username and password.
* To protect passwords using bcrypt hashing.
* To prevent SQL injection attacks using parameterized SQL queries.
* To maintain user sessions after successful login.
* To provide a secure logout mechanism.

## Technologies Used

* Python 3.x
* Flask Web Framework
* SQLite Database
* bcrypt Library
* HTML and CSS

## Project Features

* User Registration
* Secure User Login
* Password Hashing using bcrypt
* SQL Injection Protection
* Session Management
* Dashboard Access Control
* Logout Functionality
* Login Activity Report Generation

## Project Structure

secure_login_system/

├── app.py - Main Flask application

├── users.db - SQLite database

├── requirements.txt - Required Python packages

├── templates - HTML files for user interface

├── reports - Stores login reports

├── README.txt - Project documentation

└── Project_Report.pdf - Detailed project report

## Installation and Execution

Step 1: Install Python on your system.

Step 2: Install the required packages:

pip install -r requirements.txt

Step 3: Run the Flask application:

python app.py

Step 4: Open a web browser and visit:

http://127.0.0.1:5000

## Working Procedure

1. New users create an account using the registration page.
2. The password is encrypted using bcrypt before storing it in the database.
3. Registered users can log in with valid credentials.
4. The system verifies the password using bcrypt hash comparison.
5. After successful authentication, a user session is created.
6. The user can access the dashboard and logout securely.

## Security Mechanisms Implemented

### Password Hashing

User passwords are converted into bcrypt hashes before storing them in the database, protecting them from unauthorized access.

### SQL Injection Protection

Parameterized queries are used to separate user input from SQL commands, preventing SQL injection attacks.

### Session Management

Flask sessions are used to maintain authenticated user access and prevent unauthorized dashboard access.

### Logout Security

The user session is cleared when the logout option is selected.

## Future Enhancements

* Two-Factor Authentication (2FA)
* Email Verification
* Password Reset Functionality
* Strong Password Validation
* Login Attempt Limitation
* HTTPS Deployment

## Conclusion

The Secure Login System demonstrates fundamental web application security concepts such as secure authentication, password protection, database security, and session handling. The project provides a strong foundation for developing secure web applications.

## Developed By

Kishore L S
Cybersecurity Intern
