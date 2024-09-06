Zoo Database Management System

This project is a Zoo Database Management System developed using PHP, HTML, CSS, XAMPP, and SQL. It is designed to manage the data related to animals, enclosures, zookeepers, and visitors, providing a smooth interface for administrators to maintain records effectively.

Features

Animal Management: Add, update, and delete information related to animals, including species, age, habitat, and health status.
Enclosure Management: Track information about different enclosures and assign animals to them.
Zookeeper Management: Keep records of zookeepers, their assigned animals, and enclosures.
Visitor Information: Maintain a log of visitor details, tickets, and interactions with the zoo.
Search Functionality: Easily search and filter data for animals, enclosures, or personnel.
Login System: Secure authentication for administrators to access and manage the database.
Responsive Design: User-friendly interface with HTML and CSS for smooth interaction across devices.

Tech Stack

Backend: PHP
Frontend: HTML, CSS
Database: MySQL (Managed via XAMPP)
Development Environment: XAMPP (Apache + MySQL)

Installation

Prerequisites

XAMPP: Download and install XAMPP.
Web Browser: Chrome, Firefox, or any other modern browser.

Setup Steps

Clone the repository:

git clone https://github.com/Sharanagouda-01/Zoo-DBMS-Project.git

Start XAMPP:

Open XAMPP and start the Apache and MySQL modules.

Database Configuration:

Open phpMyAdmin in your browser.
Create a new database named zoo_db.
Import the provided SQL file (zoo_db.sql) from the database/ folder.

Configure Database Connection:

Open the config.php file in the project directory.
Set the database connection details (host, username, password, and database name):

$host = 'localhost';
$db   = 'zoo_db';
$user = 'root';
$pass = '';

Run the Project:

Place the project folder in the htdocs directory (usually found under C:\xampp\htdocs).
Open your browser and navigate to http://localhost/zoo-dbms.

Usage

Login: Admins can log in using the credentials set in the database.
Dashboard: Upon login, access the admin dashboard to manage animals, enclosures, zookeepers, and visitors.

Screenshots

Include screenshots of your interface, such as the login page, admin dashboard, and data entry forms.

Contributing

If you'd like to contribute to the project, please fork the repository and use a feature branch. Pull requests are warmly welcome.
