# DevSpot – Job Board Web Application

## 📌 Overview

DevSpot is a web application for posting and browsing developer job listings.
It allows users with different roles to create, view, and manage job postings.

This project demonstrates the use of ASP.NET Core MVC, authentication and authorization with ASP.NET Identity, as well as the Repository pattern and unit testing.

---

## 🚀 Features

* 🔐 Authentication & Authorization (ASP.NET Identity)
* 👤 Role-based access:

  * **Admin** – can manage all job postings
  * **Employer** – can manage only their own postings
* 📄 View all job postings
* ➕ Create job postings
* ❌ Delete job postings (AJAX)
* 🔎 Filter postings by user
* 🧪 Unit tests for business logic

---

## 🛠️ Technologies Used

* ASP.NET Core MVC
* C#
* Entity Framework Core
* ASP.NET Identity
* Repository Pattern
* xUnit
* Moq
* jQuery (AJAX)
* Bootstrap

---

## 🧱 Architecture

The application uses:

* **ASP.NET Identity** for authentication and user management
* **Repository Pattern** to abstract data access
* **Dependency Injection** for better maintainability and testability
* **MVC pattern** for application structure

---

## 🧪 Unit Testing

The application includes unit tests for core functionality.

Tests cover:

* ✔️ Creating job postings
* ✔️ Deleting job postings
* ✔️ Authorization checks (ownership validation)
* ✔️ Repository operations

### 🛠️ Testing Tools

* xUnit
* Moq

### ▶️ Run tests

```bash
dotnet test
```

---

## ⚙️ Setup & Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/devspot.git
```

2. Open the project in Visual Studio

3. Apply migrations:

```bash
Update-Database
```

4. Run the application:

```bash
dotnet run
```

---

## 🔑 Roles

* **Admin** – full access to all job postings
* **Employer** – can manage only their own postings

---

## 📷 Screenshots


---


---

## 📄 License

This project was created for educational purposes.
