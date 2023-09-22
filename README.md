# Hospital-Management-System

## Table of Contents
Introduction
Features
Requirements
Installation
Usage
Contributing

## Introduction
The Hospital Management System is a web-based application developed to streamline hospital operations, making it easier for patients to book appointments, doctors to manage patient data, and administrators to oversee the entire system.

This system is built using PHP and XAMPP and aims to improve the efficiency of hospital processes, reduce paperwork, and enhance patient care.

## Features
User Roles:

Patients: Can register, schedule appointments, and view medical records.
Doctors: Manage their profiles, view patient information, and set availability.
Administrators: Oversee the system, manage user accounts, and monitor appointments.
Appointment Management:
Patients can book appointments with preferred doctors.
Doctors can accept or reject appointment requests.
Automatic email notifications for appointment confirmations and reminders.
Patient and Doctor Profiles:

Patients can update their personal information.
Doctors can add/edit their qualifications and expertise.

## Requirements
XAMPP (or similar PHP development environment)
MySQL database
Web browser (Chrome, Firefox, etc.)
Installation

Clone the Repository:
bash
Copy code
git clone https://github.com/amarjeet2611/hospital-management-system.git

## Database Setup:

Create a new MySQL database for the system.
Import the SQL schema file from database/hospital_management.sql into your database.
Configuration:

Update the database connection settings in config.php.
Start the Server:

Make sure your XAMPP server is running.
Place the project files in your web server's root directory (usually htdocs for XAMPP).

## Usage
Open a web browser and navigate to http://localhost/hospital-management-system (or your project's URL).
Login with your user credentials (admin, doctor, or patient).
Explore and use the system based on your role.

## Contributing
We welcome contributions to improve the Hospital Management System. To contribute:

Fork the repository.
Create a branch: git checkout -b feature/your-feature.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/your-feature.
Create a pull request.
