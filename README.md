# University Consultation System

## Description
The University Consultation System is a web-based platform designed to streamline the process of scheduling and managing off-class consultations between university students and faculty members. It provides a structured environment for students to book appointments and for teachers to manage their availability, enhancing academic communication and support.

## Features

### Role-Based Access Control
The system features three distinct user roles, each with a dedicated dashboard:

#### 1. Admin
- **User Management**: Add, update, and remove student and teacher accounts.
- **Course Management**: Create and manage courses offered by the university.
- **System Oversight**: Monitor overall system usage and data.

#### 2. Teacher
- **Schedule Management**: Set and update consultation routines and availability slots.
- **Request Handling**: View, approve, or reject student consultation requests.
- **Feedback**: View ratings and feedback provided by students.

#### 3. Student
- **Consultation Booking**: Browse teacher schedules and book available consultation slots.
- **Course Enrollment**: Enroll in courses to access relevant teacher consultations.
- **Rating System**: Rate teachers based on consultation experiences.
- **Dashboard**: View upcoming appointments and status of booking requests.

## Technologies Used
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript

## Installation and Setup

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/University-Consultation-system_project_cse370_BracU.git
    ```

2.  **Database Configuration**
    - Create a MySQL database (e.g., `university_consultation_system`).
    - Import the provided SQL file: `university_consultation_system(5).sql` into your database.

3.  **Connect to Database**
    - Open `includes/db_connect.php`.
    - Update the database credentials (host, username, password, database name) to match your local environment.

4.  **Run the Application**
    - Host the project directory on a local server environment like XAMPP, WAMP, or LAMP.
    - Access the application via your browser (e.g., `http://localhost/Project University consulation system/`).

## Usage
- **Login**: Use the login page to access your respective dashboard (Admin, Teacher, or Student).
- **Navigation**: Use the sidebar or menu options to navigate through the available features for your role.

## License
This project is licensed under the [MIT License](LICENSE).
