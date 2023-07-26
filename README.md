# ExpenseTracker

## Overview
Expense Tracker is a web application built using ASP.NET Core that allows users to track their expenses and manage their financial transactions easily. The application provides a user-friendly interface to add, edit, and delete transactions, and categorize them based on different expense types.

## Features
Add and manage financial transactions, including amount, note, and date.  
Categorize transactions into different expense types (e.g., Income, Expense) using predefined categories.  
View transaction history and summary of expenses in a dashboard.  
User-friendly interface with responsive design for various devices.  

## Technologies Used
Backend: ASP.NET Core, C#, Entity Framework Core  
Frontend: HTML, CSS, JavaScript, Bootstrap, jQuery, Syncfusion (for dropdown lists)  
Database: SQL Server (Local SQLExpress Server)  
Integrated Development Environment (IDE): Visual Studio 2022 (or a recent version)  
Version Control: Git  
Hosting: GitHub  

## Getting Started
Clone the repository to your local machine using the following command:

```sh
git clone https://github.com/maanasd/ExpenseTracker
```

Open the project in Visual Studio (or your preferred IDE).

Set up the SQL Server database connection in the appsettings.json file.

Run the database migrations to create the required tables:

```sh
dotnet ef database update
```

Build and run the application:

```sh
dotnet run
```
Access the Expense Tracker application in your web browser at http://localhost:5000 or http://localhost:5001 (depending on the configuration).

## Screenshots

![image](https://github.com/maanasd/ExpenseTracker/assets/43321563/02c64433-0efb-455b-a98d-6b44fbcc4e84)

![image](https://github.com/maanasd/ExpenseTracker/assets/43321563/1c72dd11-f0c3-45aa-9807-776dc000c6fb)

![image](https://github.com/maanasd/ExpenseTracker/assets/43321563/7e728ffb-0c47-4f67-a794-33e79af1f296)

![image](https://github.com/maanasd/ExpenseTracker/assets/43321563/486ec692-68d1-4c44-ba6b-e5fea2ffd8c2)

