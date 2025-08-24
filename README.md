BulkyWeb

BulkyWeb is a web application built using ASP.NET Core MVC, Entity Framework Core, and SQL Server. This project demonstrates CRUD operations, relational database handling, and a clean MVC architecture.

Features

User-friendly interface with MVC architecture
CRUD operations (Create, Read, Update, Delete) using Entity Framework Core
SQL Server database integration
Responsive design
Role-based authentication (if implemented)

Tech Stack

Backend: ASP.NET Core MVC
ORM: Entity Framework Core
Database: SQL Server
Frontend: HTML, CSS, JavaScript, Bootstrap (if used)

Prerequisites

Make sure you have the following installed:
.NET 7/8 SDK
SQL Server
Visual Studio 2022 or later (for full project support

Setup

Clone the repo:
git clone https://github.com/dhanyasri20/BulkyWeb.git
cd BulkyWeb

Open Bulky.sln in Visual Studio.
Update the connection string in appsettings.json:

"DefaultConnection": "Server=YOUR_SERVER_NAME;Database=BulkyDB;Trusted_Connection=True;MultipleActiveResultSets=true"

Apply migrations:
Update-Database

Run the project with F5 or Ctrl+F5.

Contributing
Fork the repo → Create a branch → Commit changes → Push → Open a Pull Request.

License
MIT License.
