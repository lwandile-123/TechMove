Link to loom video below:

https://www.loom.com/share/4cdc2d9a97af4274b38b20e61f5d2071


Global Logistics Management System (GLMS) — Visual Studio 2022 Solution
This folder contains a complete ASP.NET Core MVC 8 monolithic prototype for TechMove Logistics.
Included projects
GLMS.Web — ASP.NET Core MVC web app
GLMS.Core — entities and interfaces
GLMS.Infrastructure — EF Core DbContext, SQL Server integration, services and business logic
GLMS.Tests — xUnit unit tests

Features implemented
SQL Server database using Entity Framework Core
Models: Client, Contract, ServiceRequest
Contract status workflow: Service Requests only allowed for Active contracts
LINQ search/filter by contract date range and status
PDF-only signed agreement upload and download
External USD-to-ZAR exchange rate API using HttpClient
Auto-calculation of ZAR cost from USD on the Service Request creation page
xUnit tests for currency conversion, PDF validation and contract workflow rules
Premium dark dashboard UI

How to run in Visual Studio 2022

Extract the ZIP file.
Open GLMS.sln in Visual Studio 2022.
Make sure GLMS.Web is set as the startup project.
Open Tools > NuGet Package Manager > Package Manager Console.
Run:
Press F5 or click Run.
Run tests
In Visual Studio: Test > Test Explorer > Run All Tests.

