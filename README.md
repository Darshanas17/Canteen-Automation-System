# 🍽️ Canteen Automation System

## 📌 Overview
The **Canteen Automation System** is a web-based application designed to streamline the ordering and management process in a canteen. It allows users to browse the menu, place orders, and manage transactions efficiently, reducing wait times and enhancing customer experience.

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, Bootstrap, JavaScript, jQuery, AJAX
- **Backend:** PHP
- **Database:** MySQL
- **Server Environment:** XAMPP

## 🚀 Features
- User-friendly interface for placing orders
- Admin dashboard for managing orders, inventory, and users
- Secure authentication system for customers and admins
- Real-time order tracking and status updates
- Reports and analytics for better decision-making


## ▶️ How to Run the Project (Locally with XAMPP)

1. **Download & Install XAMPP**
   - [Download XAMPP](https://www.apachefriends.org/download.html) (Version 7.3+ recommended)

2. **Clone the Repository**
   ```bash
   git clone https://github.com/Darshanas17/Canteen-Automation-System.git
   cd Canteen-Automation-System
   ```

3. **Move Project to XAMPP htdocs Folder**
   - Copy the project folder to `C:\xampp\htdocs\`

4. **Start XAMPP & Create Database**
   - Open **XAMPP Control Panel**, start **Apache & MySQL**
   - Go to `http://localhost/phpmyadmin/`
   - Create a database **canteen_db**
   - Import the SQL file from the `SQL/` folder

5. **Configure Database Connection**
   - Open `includes/config.php`
   - Update database credentials if needed:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "canteen_db";
     ```

6. **Run the Project**
   - Open browser and go to:
     ```
     http://localhost/Canteen-Automation-System/
     ```

## 🔑 Admin Login Credentials (Default)
- **Username:** `admin`
- **Password:** `123456`

## 🌐 Hosting Options
- **For Local Testing:** Use **XAMPP**
- **For Online Hosting:** Use **InfinityFree, 000WebHost, or Hostinger**
- **Frontend on Netlify?** Needs separate backend hosting

## 📬 Contact
For any queries or collaboration, feel free to reach out!

---
⚠️ *This project is for educational purposes. Ensure proper security measures before deploying in production.*
