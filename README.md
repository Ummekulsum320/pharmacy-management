# Pharmacy Management System (PMS)

## 📌 Overview

The Pharmacy Management System is a web-based application built using **PHP and MySQL**.
It allows pharmacy staff to manage medicines, prescriptions, staff, and sales effectively.

## 🚀 Features

* Multi-user login (Admin, Manager, Pharmacist, Salesman).
* Medicine inventory management.
* Add, edit, and delete prescriptions.
* Staff management (add/remove/update Pharmacist, Manager, Salesman).
* Sales billing and receipt printing.
* Stock monitoring and expiry tracking.

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, Bootstrap, jQuery, FontAwesome
* **Backend:** PHP (Core PHP)
* **Database:** MySQL

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pharmacy-management.git
cd pharmacy-management/PMS
```

### 2. Setup Database

1. Open **phpMyAdmin** or MySQL CLI.
2. Create a new database:

   ```sql
   CREATE DATABASE pms_db;
   ```
3. Import the SQL file:

   * Go to **phpMyAdmin** → Select `pms_db` → Import → Choose `pms_db.sql` from the `database file` folder.

### 3. Configure Database Connection

* Open the `includes` folder (e.g., `config.php` or `db.php`).
* Update with your local database credentials:

  ```php
  $host = "localhost";
  $user = "root";
  $password = "";
  $dbname = "pms_db";
  ```

  *(Default XAMPP/WAMP setup uses `root` with no password.)*

### 4. Run the Project

1. Copy the `PMS` folder into your web server directory:

   * For **XAMPP** → `htdocs/`
   * For **WAMP** → `www/`
2. Start Apache and MySQL.
3. Open browser and go to:

   ```
   http://localhost/PMS
   ```

### 5. Default Login Credentials

* **Username:** `admin`
* **Password:** `admin`

## 📸 Screenshots

(Add UI screenshots here for login, dashboard, and management pages.)

## 📜 License

This project is licensed under the MIT License.

