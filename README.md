# Student Management Application

## Introduction
This is a web-based student management application developed using PHP, MySQL, and Bootstrap. It provides the functionality to manage students, including adding new students, viewing the list of students, and searching students by various criteria such as name, class, or admission number. The application supports CRUD (Create, Read, Update, Delete) operations and can be extended with more features as needed.

## Features
- Add new students with details like name, class, admission number, and more.
- View the list of all students.
- Search students by name, class, admission number, or any other field.
- Edit student details.
- Delete student records.

## Installation

### Prerequisites
- WAMP or XAMPP server (for running PHP and MySQL)
- Web browser (Chrome, Firefox, etc.)

### Steps
1. **Clone or download the repository:**



2. **Set up the database:**
- Create a new MySQL database.
- Import the provided SQL script (`database.sql`) into your MySQL database to create the necessary tables.

3. **Configure the database:**
- Edit the `db.php` file to match your MySQL credentials:
  ```php
  <?php
  $host = 'localhost';
  $db   = 'your_database_name';
  $user = 'root'; // or your MySQL username
  $pass = 'your_password'; // MySQL password
  ?>
  ```

4. **Run the application:**
- Start your WAMP or XAMPP server.
- Place the project folder inside the `www` or `htdocs` directory of your server.
- Open your browser and go to `http://localhost/project_folder_name`.

5. **Search and Manage Students:**
- Use the student list page to view all students.
- Use the search functionality to find students by name, class, or admission number.

## File Structure
- `index.php` – The main page to add and view students.
- `add_student.php` – Form to add a new student.
- `list_students.php` – Displays the list of students.
- `db.php` – Database connection file.
- `edit_student.php` – Edit student information.
- `delete_student.php` – Script to delete student records.
- `search.php` – Script to handle searching by various criteria.
- `style.css` – Custom CSS for styling the application.

## Technologies Used
- **Frontend:** HTML, CSS (Bootstrap)
- **Backend:** PHP
- **Database:** MySQL

## Future Improvements
- Implement authentication for users (admin/teacher login).
- Add the ability to export student data as PDF or CSV.
- Add pagination to the student list for better navigation.

## Author
- **Name:** Mohd Hamzah
- **Email:** mhd123hamzah@gmail.com
