# Full-Stack-Translation-Website

# Project Setup Guide

Welcome to the **Full Stack Translation Website**! Follow the instructions below to set up and run the project locally on your system using XAMPP.

# Screenshots-
![Screenshot 2024-12-04 235714](https://github.com/user-attachments/assets/8eba28d4-65d4-48e0-95eb-5d7a656b49f8)
![Screenshot 2024-12-04 235650](https://github.com/user-attachments/assets/cdf9f3b3-f485-410f-8da6-5302a7f90116)
![Screenshot 2024-12-04 235643](https://github.com/user-attachments/assets/4101289e-7805-4188-bd49-ff1071560105)
![Screenshot 2024-12-04 235620](https://github.com/user-attachments/assets/541ffdfa-11b1-4f06-8342-cca92772ecfe)
![Screenshot 2024-12-04 235608](https://github.com/user-attachments/assets/a940ab39-d05b-44d3-ae39-c95a28d11a5e)
![Screenshot 2024-12-04 235553](https://github.com/user-attachments/assets/aeb63a46-8b7f-4c15-a6d3-37f72a449aa2)


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
