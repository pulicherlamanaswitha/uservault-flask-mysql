# UserVault – Secure User Registration System

## Overview

UserVault is a web-based user registration system developed using Flask, HTML, CSS, and MySQL. The application allows users to enter their name and email address through a modern and interactive interface. Submitted information is securely stored in a MySQL database and a success message is displayed on the same page.

## Features

* User-friendly registration form
* Name and Email data collection
* MySQL database integration
* Automatic database table creation
* Modern glassmorphism user interface
* Animated gradient background
* Responsive design
* Success message after data submission
* Built using Flask framework

## Technologies Used

### Frontend

* HTML5
* CSS3
* Jinja2 Templates

### Backend

* Python
* Flask

### Database

* MySQL

## Project Structure

project/

│

├── app.py

│

└── templates/

    └── front.html

## Database Setup

Create a database in MySQL:

```sql
CREATE DATABASE htmlworking;
```

The application automatically creates the required table:

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    email VARCHAR(255)
);
```

## Installation

### Install Required Packages

```bash
pip install flask mysql-connector-python
```

### Run the Application

```bash
python app.py
```

Open the browser and visit:

```text
http://127.0.0.1:5000
```

## Workflow

1. User enters Name and Email.
2. User clicks Submit.
3. Data is sent to Flask backend.
4. Flask stores the data in MySQL.
5. Success message is displayed.
6. User information is permanently stored in the database.

## Future Enhancements

* View registered users
* Edit user information
* Delete user records
* Search functionality
* Export data to CSV
* User authentication system
* Dashboard analytics

## Author

Developed using Python Flask and MySQL as a mini web application project.

## Conclusion

UserVault demonstrates the integration of frontend technologies, Flask backend development, and MySQL database management to build a complete user registration system with an attractive user interface.
