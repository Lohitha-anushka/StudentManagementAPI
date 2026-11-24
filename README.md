# Student Management API

ASP.NET Core Web API (.NET 8) with SQL Server LocalDB.
Has CRUD for students and two custom middleware (request logging and error handling).

## How to run
1. Run Database/StudentAPI.sql in SQL Server.
2. Open StudentManagementAPI.sln in Visual Studio.
3. Press F5. Swagger opens at https://localhost:7088/swagger

## Folders
- Controllers - StudentsController (GET, POST, PUT, DELETE)
- Models - Student class
- Middleware - RequestLoggingMiddleware, ExceptionHandlingMiddleware
- Database - SQL script
