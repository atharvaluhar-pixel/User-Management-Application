User Management Web Application

Description

This is a simple web application for managing users. You can add, list, edit, and delete users. It uses a website (frontend) built with HTML, CSS (Bootstrap), and JavaScript, and a backend built with ASP.NET Core and SQLite database.

Features





List Users: See all users in a table with their name, email, birth date, and registration date.



Add User: Fill a form to add a new user.



Edit User: Click "Edit" to update a user's details.



Delete User: Click "Delete" to remove a user.



Validation: Checks for valid email and required fields.



The frontend talks to the backend using RESTful API calls (GET, POST, PUT, DELETE).

How to Run

Follow these steps to set up and run the project:





Prerequisites:





Install Visual Studio Community 2022 with the “ASP.NET and web development” workload.



Setup:





Open the UserManagementApp.sln file in Visual Studio.



In Visual Studio, go to “Tools” > “NuGet Package Manager” > “Manage NuGet Packages for Solution” and ensure Microsoft.EntityFrameworkCore.Sqlite and Microsoft.EntityFrameworkCore.Design are installed.



In the Package Manager Console, run:

Add-Migration InitialCreate
Update-Database

This creates the SQLite database (users.db).



Run:





Click the green “Run” button in Visual Studio (or press F5).



Your browser will open to https://localhost:xxxx (port may vary).



Database:





The database is a SQLite file (users.db) in the project folder.
