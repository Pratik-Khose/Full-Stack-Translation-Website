# Full-Stack-Translation-Website

# Project Setup Guide

Welcome to the **[Project Name]**! Follow the instructions below to set up and run the project locally on your system using XAMPP.

---

## Prerequisites

1. Install [XAMPP](https://www.apachefriends.org/index.html) on your system.
2. Ensure the following services are available:
   - **Apache Server**
   - **MySQL Database**
3. Clone this repository to your local machine.

---

## Setup Steps

### 1. Clone the Repository
Clone the project repository using the following command:
```bash
git clone <https://github.com/Pratik-Khose/Full-Stack-Translation-Website.git>
```

### 2. Move the Project to XAMPP's `htdocs`

1. Copy the cloned project folder.
2. Navigate to the XAMPP installation directory on your system.
   - Example: `C:\xampp\htdocs` on Windows.
3. Paste the project folder inside the `htdocs` directory.

### 3. Start XAMPP Services

1. Open the XAMPP Control Panel.
2. Start the **Apache Server** and **MySQL Server**.

### 4. Create the Database

1. Open [phpMyAdmin](http://localhost/phpmyadmin/) in your browser.
2. Create a new database with the name:
3. Inside the `superfinal` database, create a table named: tbl_user

### 5. Import the Database File

1. Locate the database file in the `database` folder of the source code: /path/to/source-code/database/db_file.sql
2. Import this `.sql` file into the `superfinal` database using phpMyAdmin:
- Go to the **Import** tab in phpMyAdmin.
- Choose the `db_file.sql` file.
- Click **Go** to complete the import.

### 6. Access the Project

1. Open your browser and navigate to: http://localhost/<folder-name>
Replace `<folder-name>` with the name of the project folder you pasted in the `htdocs` directory.
2. The project should now be running successfully!

### Additional Notes

- Ensure that your XAMPP services are running whenever you access the project.
- For any issues or questions, please check the project documentation or contact the project maintainer.
