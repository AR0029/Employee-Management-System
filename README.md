**Employee Management System**

**📌 Project Overview**

  The Employee Management System is a web and mobile-based application that allows users to manage employee records efficiently. This project is built using Apache Cordova, PHP, MySQL, and DataTables to provide   an interactive employee dashboard with CRUD functionalities.

**📌 Technologies Used**

  **Frontend**: Apache Cordova, HTML, CSS, JavaScript, jQuery, Bootstrap

  **Backend**: PHP (REST API)

  **Database**: MySQL

  **Additional Libraries**: DataTables for sorting, filtering, and pagination

**📌 1️⃣ How to Set Up and Run the Project**

**🔹 Step 1: Install Required Software**

  Before running the project, ensure you have installed:
  ✅ XAMPP (For Apache & MySQL) – Download
  ✅ Node.js & npm (For Cordova) – Download
  ✅ Apache Cordova (For Mobile UI) – Installed via npm
  ✅ Android Studio (For building APK) – Download
  ✅ VS Code (For editing & running the project) – Download

**🔹 Step 2: Set Up the Backend (PHP & MySQL)**

  Start XAMPP:

  Open XAMPP Control Panel

  Click Start on Apache and MySQL

  Open phpMyAdmin:

  Go to http://localhost/phpmyadmin/

  Create the Database:

  Click Databases → Create a new database named employee_db.

  Import SQL Schema:

  Open phpMyAdmin

  Select employee_db

  Click Import → Choose database.sql (if provided) → Click Go

**🔹 Step 3: Configure Backend API**

  Open VS Code and navigate to:

  C:\xampp\htdocs\employee_management\

  Ensure api.php is inside this folder with correct database credentials.

  Run the PHP server:

  php -S localhost:8000

  Test API in Browser:
  Open http://localhost:8000/api.php?action=getEmployees

  ✅ If you see JSON data, the backend is working!

**🔹 Step 4: Set Up the Frontend (Cordova App)**

  Open VS Code and navigate to:

  C:\xampp\htdocs\employee_management\employee_app\

  Ensure index.html and app.js are inside www/ folder.

  Add Apache Cordova browser support:

  cordova platform add browser

  Run the Cordova app in a browser:

  cordova run browser

  ✅ The Employee Dashboard should now open!

**📌 2️⃣ Building and Running the APK**

**🔹 Step 5: Build the APK for Android**

  Add the Android platform:

  cordova platform add android

  Build the APK:

  cordova build android

  Find the APK file:

  C:\xampp\htdocs\employee_management\employee_app\platforms\android\app\build\outputs\apk\debug\

  ✅ The file app-debug.apk is your final APK.

**📌 3️⃣ Final Submission**

**🔹 Submit the Following Files:**

  APK File: app-debug.apk

  Project ZIP File: Employee_Management_Project.zip (Contains Backend + Frontend)

  README.txt (This File)



**📌 4️⃣ Features Implemented**

  ✅ Employee Dashboard with sorting, filtering, and pagination using DataTables
  ✅ CRUD Operations (Add, Edit, Delete Employees)
  ✅ REST API for fetching employee data from MySQL
  ✅ Mobile App built with Apache Cordova for Android
