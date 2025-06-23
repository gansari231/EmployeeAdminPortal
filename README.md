# 📘 Employee Admin Portal API

## 🏢 Overview

This is a **CRUD API** built with **ASP.NET Core** for managing employee records in an admin portal. It provides endpoints to create, read, update, and delete employee data.

---

## 🚀 Features

- ✅ Create new employee records  
- ✅ Get all employees or a single employee by ID  
- ✅ Update existing employee records  
- ✅ Delete employee entries  
- 🔐 Easily extendable for authentication/authorization  
- 📦 Clean architecture with separation of concerns  

---

## ⚙️ Tech Stack

- **Framework**: ASP.NET Core Web API  
- **Language**: C#  
- **Database**: SQL Server / SQLite / InMemory (based on configuration)  
- **ORM**: Entity Framework Core  
- **Tools**: Swagger UI, LINQ, Dependency Injection 

---

## 🛠️ API Endpoints

| Method | Endpoint               | Description                    |
|--------|------------------------|--------------------------------|
| GET    | `/api/employees`       | Retrieve all employees         |
| GET    | `/api/employees/{id}`  | Retrieve a specific employee   |
| POST   | `/api/employees`       | Add a new employee             |
| PUT    | `/api/employees/{id}`  | Update an employee's details   |
| DELETE | `/api/employees/{id}`  | Delete an employee             |

---

## 📦 Sample Employee JSON

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john.doe@example.com",
  "department": "Engineering",
  "designation": "Backend Developer",
  "salary": 75000
}
```

---

## ▶️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/employee-admin-api.git
   cd employee-admin-api
   ```

2. **Restore and build the project**
   ```bash
   dotnet restore
   dotnet build
   ```

3. **Run the application**
   ```bash
   dotnet run
   ```

4. **Access Swagger UI**
   ```
   https://localhost:{port}/swagger
   ```

---

## 💡 Extras

- All endpoints use `async/await` for non-blocking I/O operations.
- Clean and maintainable structure with:
  - Controllers
  - Services
  - DTOs
  - Models
- Easily extendable for:
  - JWT Authentication
  - Caching (e.g., IMemoryCache)
  - Role-based access
  - Advanced error handling and logging

---

## 👨‍💻 Author

Developed by Gufraan Ansari 
LinkedIn: https://linkedin.com/in/your-profile  
GitHub: https://github.com/your-username  
Email: ansarigufraan0@gmail.com
