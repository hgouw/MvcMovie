DO NOT forget to delete the folder Migrations before doing the steps below
==========================================================================

ASP.NET Core MVC with EF Core - Migrations

https://docs.microsoft.com/en-us/aspnet/core/data/ef-mvc/migrations?view=aspnetcore-2.1
https://docs.microsoft.com/en-us/ef/core/miscellaneous/cli/dotnet
https://docs.microsoft.com/en-us/ef/core/miscellaneous/cli/powershell

EF Core Package Manager Console Tools
=====================================
Install-Package Microsoft.EntityFrameworkCore.Tools
Add-Migration Initial
Update-Database

EF Core .NET Command-line Tools
===============================
dotnet ef migrations add Initial
dotnet ef database update