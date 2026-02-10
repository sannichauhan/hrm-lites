# HRMS Lites - Human Resource Management System

A modern, scalable full-stack web application designed to manage employee records and track daily attendance efficiently, developed with React for the frontend, Django for the backend, and PostgreSQL as the database.

## Employee Management

-Add new employees with built-in form validation
-View all employees in a responsive, card-based interface
-Search employees by name, ID, email, or department
-Remove employee records securely
-Prevent duplicate employee IDs and email addresses

## Attendance Management

-Record daily attendance with present/absent status
-View attendance records in a structured table layout
-Filter attendance entries by employee name or date
-Block duplicate attendance entries for the same employee and date
-Automatically validate attendance dates

## Dashboard

-Display real-time overview of key statistics
-Show total number of registered employees
-Provide a summary of today’s attendance
-Highlight present and absent employee counts

## For Frontend

-React 18 – Modern JavaScript library for building user interfaces
-Vite – High-performance development server and build tool
-React Router – Client-side navigation and route management
-Axios – Promise-based HTTP client for API communication
-CSS – Custom styling using modern CSS features and variables

## Backend

-Django – High-level Python web framework for rapid and secure development
-PostgreSQL – Robust relational database for reliable data storage
-Django REST Framework – Toolkit for building RESTful APIs

## Prerequisites

-Node.js (v18 or later) with npm
-Python (v3.9 or higher)
-PostgreSQL (v12 or newer)

## For Local Setup

## 1. Clone the Repository

```cmd
git clone https://github.com/sannichauhan/hrm-lites
cd hrm-lites
```


### 2. For Backend Setup

```CMD
git clone https://github.com/sannichauhan/hrm-lites
cd hrm-lites

# Create virtual environment
python -m venv env

# Activate virtual environment
# Windows:
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
python .\manage.py makemigrations 
python .\manage.py migrate  
python .\manage.py runserver  
```

## For Frontend setup on local
```CMD
git clone https://github.com/sannichauhan/hr-frontend
cd hr-frontend

# Install dependencies
npm install

# Run development server
npm run dev
```

The frontend will be available at `http://localhost:5173`
```