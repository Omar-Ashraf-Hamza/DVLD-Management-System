# DVLD - Driving & Vehicle License Department Management System

A desktop application designed to manage driving and vehicle license department operations, including people, drivers, applications, and licenses.

## 📌 Project Overview

The **DVLD Management System** is a Windows desktop application built using C# and .NET. It helps organize and manage the main operations of a driving and vehicle licensing department through a structured and maintainable application.

The project follows a **Three-Tier Architecture** to separate the presentation, business logic, and data access responsibilities.

## 🏗️ Architecture

The application is organized into three main layers:

### 1. Presentation Layer
- Provides the graphical user interface.
- Handles user interactions.
- Displays information and application results.

### 2. Business Logic Layer
- Contains the application's business rules.
- Processes application operations.
- Connects the presentation layer with the data access layer.

### 3. Data Access Layer
- Handles communication with the SQL Server database.
- Executes database operations.
- Retrieves and updates application data.

## 🛠️ Technologies Used

- **C#**
- **.NET Framework**
- **Windows Forms (WinForms)**
- **Microsoft SQL Server**
- **ADO.NET**
- **Visual Studio**

## ✨ Main Features

- People Management
- Drivers Management
- Local Driving License Applications
- License Management
- International Driving Licenses
- Application Management
- User Management

## 📂 Project Structure

```text
DVLD-Management-System/
│
├── DVLD/
│   ├── Presentation Layer
│   ├── Forms
│   ├── User Controls
│   └── App.config
│
├── DVLD_Buisness/
│   └── Business Logic Layer
│
├── DVLD_DataAccess/
│   └── Data Access Layer
│
├── .gitignore
└── README.md
```

## ⚙️ Requirements

- Windows
- Visual Studio 2022
- .NET Framework (the version configured in the project)
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Omar-Ashraf-Hamza/DVLD-Management-System.git
   ```

2. Open the solution file `DVLD.sln` inside the `DVLD` folder using Visual Studio.

3. Create and configure the required SQL Server database.

4. Check the database connection string in `App.config` and update the server name if necessary.

5. Build and run the application.

## 🗄️ Database Configuration

The application uses SQL Server with Windows Authentication.

Make sure the database is created and configured correctly before running the application.

## 👨‍💻 Author

**Omar Ashraf Hamza**

- GitHub: [Omar-Ashraf-Hamza](https://github.com/Omar-Ashraf-Hamza)

---

⭐ If you find this project useful, feel free to explore the repository.
