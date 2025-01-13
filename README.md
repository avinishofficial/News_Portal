# News Portal Project

The **News Portal Project** is a web-based application built using **PHP** and **MySQL**. It provides a platform for publishing and managing news articles. The project includes a frontend for users to browse news and an admin panel for managing the content.

---

## Features

- User-friendly interface for browsing news articles.
- Admin panel for managing news categories, articles, and users.
- Sub-admin functionality with limited access.
- Fully functional MySQL database for data storage.

---

## Requirements

- **XAMPP**, **WAMP**, or **LAMP** server environment.
- PHP version 7.x or later.
- MySQL server.

---

## Installation Steps

1. **Download the Project Files**  
   Download the ZIP file of this repository.

2. **Extract the Files**  
   Extract the ZIP file and locate the `newsportal` folder.

3. **Copy the Folder to the Server Root Directory**  
   - For **XAMPP**: Paste it inside `xampp/htdocs`.
   - For **WAMP**: Paste it inside `wamp/www`.
   - For **LAMP**: Paste it inside `var/www/html`.

4. **Set Up the Database**  
   - Open your database management tool (e.g., phpMyAdmin).
   - Create a new database named `newsportal`.
   - Import the `newsportal.sql` file located in the `sql file` folder of the extracted package.

5. **Run the Application**  
   - Open your browser and navigate to:
     - **Frontend**: [http://localhost/newsportal](http://localhost/newsportal)
     - **Admin Panel**: [http://localhost/newsportal/admin](http://localhost/newsportal/admin)

---

## Admin Panel Credentials

| Role       | Username  | Password   |
|------------|-----------|------------|
| Admin      | `admin`   | `Test@123` |
| Sub-Admin  | `subadmin`| `Test@123` |

---

## Folder Structure

