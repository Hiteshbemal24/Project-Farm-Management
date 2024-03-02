# Farming Management System

## Overview
Welcome to the Farming Management System! This application is designed to assist farmers in managing their products efficiently. With a user-friendly interface, farmers can add, buy, and sell products seamlessly. The system is built using HTML, CSS, JavaScript, Bootstrap for the frontend, and Python Flask with SQLAlchemy for the backend.

## Screenshots

[![Farming Management System](https://github.com/Hiteshbemal24/Project-Farm-Management/blob/main/Screenshots/Screenshot%20(119).png)](https://github.com/Hiteshbemal24/Project-Farm-Management/tree/main/Screenshots)


## Technologies Used
- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - Bootstrap

- **Backend:**
  - Python (3.9)
  - Flask
  - SQLAlchemy
  - XAMPP (for MySQL database)

## Setting Up the Environment

### 1. Python Virtual Environment
To ensure a clean and isolated Python environment, follow these steps to create a virtual environment:

```bash
# Navigate to your project directory
cd your_project_directory

# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
# For Windows
venv\Scripts\activate
# For macOS/Linux
source venv/bin/activate
```
### 2. Installing Required Packages
Once the virtual environment is activated, install the necessary Python packages using pip:

```bash
pip install flask flask-sqlalchemy mysqlclient flask-login
```

### 3. XAMPP Setup
Ensure that XAMPP is installed on your machine, and start the Apache and MySQL services. Create a new database for the Farming Management System.

## Running the Application
### 1.Clone the repository:
```bash
git clone https://github.com/your_username/farming-management-system.git
cd farming-management-system
```
### 2.Activate the virtual environment:
```bash
# For Windows
venv\Scripts\activate
# For macOS/Linux
source venv/bin/activate
```
### 3.Run the Flask application:
```bash
python main.py
```
### 4.Access the application in your web browser at 'http://localhost:5000'.

# Features

 - Add new products to the inventory
 - Buy products from other farmers
 - Sell products to other farmers
### Feel free to explore and customize the Farming Management System according to your needs!
