# Demo ASP.NET Core Web API

A simple ASP.NET Core Web API project demonstrating basic functionality, including:

- Entity Framework Core with SQL Server
- Swagger/OpenAPI documentation
- Configuration management
- RESTful endpoints

## Features

- Weather forecast API endpoint
- SQL Server database integration
- Swagger UI for API documentation
- Development/production environment configuration

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- SQL Server (or modify connection string for another database)

## Getting Started

1. Clone the repository:
   ```sh
   git clone https://github.com/OmarMenem8/Demo.git
   cd Demo
 2.Update the connection string in appsettings.json:
   "ConnectionStrings": {
  "DefaultConnection": "Your_Connection_String_Here"
}

3.Restore dependencies:
sh
dotnet restore

4.Run the application:
sh
dotnet run
