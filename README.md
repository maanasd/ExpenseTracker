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
Frontend: HTML, CSS, JavaScript, Bootstrap, Syncfusion
Database: SQL Server (Local SQLExpress Server)  
Integrated Development Environment (IDE): Visual Studio 2022
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

![Screenshot 2023-07-24 161130](https://github.com/maanasd/ExpenseTracker/assets/43321563/dd20b1a1-c6b1-48a5-bc7d-c470bd9af6a4)

![Screenshot 2023-07-24 161324](https://github.com/maanasd/ExpenseTracker/assets/43321563/4a3c6132-96f1-4b5c-b6dc-9d78e6ef6d5e)

![Screenshot 2023-07-24 161611](https://github.com/maanasd/ExpenseTracker/assets/43321563/96eb24f4-47f9-4635-aa4a-6e2335fe4dc9)

![Screenshot 2023-07-24 161710](https://github.com/maanasd/ExpenseTracker/assets/43321563/2d2910f5-7a1d-4ea7-82e9-74744b402032)


