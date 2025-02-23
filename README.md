Online Examination System

Project Overview

Author: Lokesh Rowthula
This project is a web-based application designed to streamline online testing for students and administrators. It provides a secure, efficient, and automated solution for conducting quizzes and exams, ensuring a comprehensive assessment experience.

Problem Statement

Develop a web-based placement examination system to assess students' potential success in computer courses or technology registrations. The system will incorporate features such as online exam creation, administration, and grading, as well as electronic journal management.

Features

Online exam creation and management

Secure authentication system for students and administrators

Multimedia content support for questions

Automated grading and result display

Electronic journal management

System Architecture



Actors:

User (Student): Takes quizzes and views results.

Admin: Manages quiz content and user data.

Components:

Web Application: User interface for accessing and taking quizzes.

Database: Stores quiz data, user information, and results.

Quiz Module: Manages quiz content and logic.

Results Module: Displays quiz results.

Workflow:

Admin logs in to manage quizzes.

Web application fetches quiz data from the database.

Users register and start the quiz.

Users submit answers, which are stored in the database.

Users receive results after completion.

UML Diagrams



Sequence diagrams for user interactions

System database flow

Authentication process overview

Technologies Used

Frontend: AngularJS, Bootstrap

Backend: PHP

Database: SQL Server

Installation and Setup

Clone the repository.

Install dependencies using npm (for frontend) and configure the PHP backend.

Set up the database using the provided SQL scripts.

Run the application on a local or hosted server.

How to Run XAMPP and Upload SQL File in MySQL

Running XAMPP:

Download and install XAMPP from Apache Friends.

Open the XAMPP Control Panel and start Apache and MySQL.

Place your project files in the htdocs folder inside the XAMPP installation directory.

Open a web browser and go to http://localhost/your_project_folder/ to access your application.

Uploading SQL File in MySQL:

Open XAMPP and start Apache and MySQL.

Open your web browser and navigate to http://localhost/phpmyadmin/.

Click on "Databases" and create a new database with a desired name.

Select the newly created database and click on the "Import" tab.

Click "Choose File" and select your .sql file.

Click "Go" to upload and execute the SQL script.

Your database is now set up and ready to use.

Testing and Quality Assurance



Test coverage analysis using JaCoCo

Performance testing with JMeter

Static code analysis via SonarQube

Conclusion

This system provides a user-friendly graphical interface with enhanced security, reliability, and efficiency. Future enhancements can be incorporated as needed.

References

AngularJS Documentation

Bootstrap

PHP Manual

SQL Server

JMeter

SonarQube

Note: Ensure all necessary dependencies and software are installed before running the application.
