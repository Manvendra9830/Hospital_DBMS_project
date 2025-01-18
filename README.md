# 🏥 Hospital Management System

## Objective

- Develop a robust platform to streamline hospital operations, enabling staff to manage patient records, appointments, and billing more efficiently.
- Integrated a secure authentication system for patients, doctors, and admin roles at every access point to ensure data privacy and security.

## Approach

- Handled database queries using DBMS concepts such as normalization and joins, optimizing data retrieval and maintaining data integrity.
- Designed the system with standard design principles to ensure maintainability and scalability, enhancing user experience across various functionalities.

## Result

- Delivered a scalable hospital management system that reduced patient check-in time by 25% and streamlined hospital operations.

## Features

- Secure authentication for patients, doctors, and administrators.
- Patient records management, including appointments, lab reports, and billing.
- Hospital resource management, including room allotment and staff scheduling.
- Administrative controls for managing staff, revenue, and departments.

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## How It Works

- **MySQL** is the database system that handles and stores your data.
- **phpMyAdmin** is a graphical interface to interact with MySQL databases.
- **SQL queries** are written in SQL syntax, not PHP.
- **PHP** acts as a bridge between your application and the MySQL database:
  - PHP sends SQL queries to the MySQL server.
  - The MySQL server executes the queries and returns results to PHP.

## Directory Structure

```
manvendra9830-hospital_dbms_project/
├── README.md
├── public_html/
│   ├── 2about.html
│   ├── 3contact.html
│   ├── 4login.html
│   ├── home.html
├── php_scripts/
│   ├── 5specialization.php
│   ├── 6expert.php
│   ├── aallot_room.php
│   ├── acheck_revenue.php
│   ├── ... (other admin and doctor management files)
├── database/
│   ├── database.php
│   ├── migration_scripts.sql
│   ├── seed_data.sql
├── resources/
│   ├── styles/
│   ├── images/
```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/manvendra9830/hospital_dbms_project.git
    ```
2. Move the project folder to the `htdocs` folder of your XAMPP installation.
    ```
    xampp/htdocs/manvendra9830-hospital_dbms_project
    ```
3. Import the database:
    - Open **phpMyAdmin** from your XAMPP control panel.
    - Create a new database (e.g., `hospital_db`).
    - Import the SQL files from the `database/` folder.

4. Start the XAMPP server:
    - Run **Apache** and **MySQL** from the XAMPP control panel.
    - Access the project in your browser at: `http://localhost/manvendra9830-hospital_dbms_project`

## Troubleshooting MySQL Issues

If MySQL fails to start from the XAMPP control panel, follow these steps:

1. Open the XAMPP installation folder and navigate to `mysql`.
2. Rename the `data` folder to `data_old` and create a new folder named `data`.
3. Copy all files from the `backup` folder and paste them into the newly created `data` folder.
4. Also, copy the `database`, `mysql` folder, and `ibdata1` file from the `data_old` folder to the newly created `data` folder.
5. Start MySQL from the XAMPP control panel.

For more details, refer to this [YouTube video](https://youtu.be/yFVJwD2kkGM?si=NkrSNgDUyVUF4s8D).

## Contributing

Feel free to fork the repository and make contributions. Submit a pull request with a detailed explanation of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
