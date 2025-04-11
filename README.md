Resident Management Module – Grama Niladhari

---------------------------------------------
Description:
---------------------------------------------
This module allows the Grama Niladhari to manage resident records including:
- Adding new residents
- Searching by name, NIC or address
- Editing resident details
- Deleting records

---------------------------------------------
How to Set Up the Project:
---------------------------------------------

1. Requirements:
- XAMPP (or any local server with PHP & MySQL)
- MySQL Workbench or phpMyAdmin

2. Setup Steps:
- Start Apache and MySQL from XAMPP.
- Copy the 'resident_module' folder into your XAMPP's htdocs directory:
  Example path: C:/xampp/htdocs/resident_module

3. Import the Database:
- Open phpMyAdmin (http://localhost/phpmyadmin)
- Create a new database called: resident_database
- Import the `residents.sql` file inside this project

4. Access the Web Module:
- Open your browser and go to:
  http://localhost/resident_module/public/add_resident.php  → To add new residents
  http://localhost/resident_module/public/search.php        → To view/edit/delete/search

---------------------------------------------
Author:
Dilanka Fernando
