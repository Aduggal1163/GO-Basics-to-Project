# 🐹 Go Course & Projects Workspace

Welcome to my personal Go development and learning workspace! This repository contains a structured, hands-on journey through the Go programming language, covering everything from fundamental syntax to advanced concurrency patterns, leading up to a production-ready web application.

---

## 🚀 Repository Overview

This workspace is structured as a series of modules, each targeting specific core concepts or projects in Go:

| Module / Directory | Description | Key Concepts Covered |
| :--- | :--- | :--- |
| 📁 [**Basics**](file:///Users/abhishekduggal/Desktop/Projects/GO/Basics) | Introduction to Go fundamentals | Variables, type inference, standard input/output, math operations. |
| 📁 [**Control Statements**](file:///Users/abhishekduggal/Desktop/Projects/GO/Control%20Statements) | Flow control inside Go | conditional checks (`if`, `else`), `switch` cases, loops. |
| 📁 [**Functions**](file:///Users/abhishekduggal/Desktop/Projects/GO/Functions) | Reusable logic building blocks | Arguments, return values, practices. |
| 📁 [**Functions2**](file:///Users/abhishekduggal/Desktop/Projects/GO/Functions2) | Advanced function structures | Recursion, variadic parameters, anonymous functions, first-class functions. |
| 📁 [**Pointers**](file:///Users/abhishekduggal/Desktop/Projects/GO/Pointers) | Accessing and managing memory | Memory addresses, dereferencing, pass-by-pointer. |
| 📁 [**Structs**](file:///Users/abhishekduggal/Desktop/Projects/GO/Structs) | Object-oriented concepts in Go | Struct custom types, pointer receivers, struct tags. |
| 📁 [**Customtype**](file:///Users/abhishekduggal/Desktop/Projects/GO/Customtype) | Creating domain-specific types | Type definition, custom methods on base types. |
| 📁 [**Arrays**](file:///Users/abhishekduggal/Desktop/Projects/GO/Arrays) | Data collections and lists | Arrays, slices, maps, slice manipulation. |
| 📁 [**Packages**](file:///Users/abhishekduggal/Desktop/Projects/GO/Packages) | Module organization | File operations, package visibility (`Capitalization`), imports. |
| 📁 [**Interface**](file:///Users/abhishekduggal/Desktop/Projects/GO/Interface) | Defining behavior and polymorphism | Interface structures, embedding interfaces, empty interfaces. |
| 📁 [**notes json**](file:///Users/abhishekduggal/Desktop/Projects/GO/notes%20json) | JSON-serialized notes tool | File handling, JSON encoding/decoding. |
| 📁 [**Generics**](file:///Users/abhishekduggal/Desktop/Projects/GO/Generics) | Reusable type-safe constructs | Type constraints, generic functions. |
| 📁 [**Concurrency**](file:///Users/abhishekduggal/Desktop/Projects/GO/Concurrency) | Multi-threaded programming | Goroutines, channels, waitgroups, select statements. |
| 📁 [**BankAccountSystem**](file:///Users/abhishekduggal/Desktop/Projects/GO/BankAccountSystem) | OOP Bank Simulator | Encapsulation, structs, package imports. |
| 📁 [**project**](file:///Users/abhishekduggal/Desktop/Projects/GO/project) | Event Booking REST API | Gin web framework, SQLite, JWT auth, middleware, DB migrations. |

---

## 🛠️ Key Projects Featured

### 1. Event Booking REST API (`/project`)
This is the capstone project of the course—a fully functional REST API designed for organizing and registering for events.
* **Framework:** [Gin Gonic](https://github.com/gin-gonic/gin) for high-performance HTTP routing.
* **Database:** SQLite3 (`api.db`) using `database/sql` driver.
* **Authentication:** JWT (JSON Web Tokens) with secure password hashing (using bcrypt).
* **Middleware:** CORS and Token Validation handlers.
* **Features:**
  * User Registration & Login (hashed credentials, JWT generation).
  * CRUD operations for Events (only accessible to authenticated owners).
  * Event Registration (allows users to RSVP/register for specific events).

### 2. Bank Account System (`/BankAccountSystem`)
A console-based simulator showcasing object-oriented patterns in Go:
* Uses package imports (`example.com/structs/account`) to achieve strict access control.
* Performs balance checks, deposits, withdrawals, and formatted displays.

---

## ⚙️ Getting Started

### Prerequisites
* Go 1.20+ installed on your system.
* SQLite3 (for running the REST API).

### How to Run the REST API
1. Navigate to the project directory:
   ```bash
   cd project
   ```
2. Initialize dependencies:
   ```bash
   go mod tidy
   ```
3. Run the application:
   ```bash
   go run main.go
   ```
4. The server will start on `http://localhost:8080`.

### How to Run Individual Exercises
For any basic lesson folder (e.g., `Generics`):
```bash
cd Generics
go run main.go
```

---

## 📜 Certification
I have successfully completed the Go course accompanying this repository. My certificate is available here:
* [🎓 GO-certificate.pdf](file:///Users/abhishekduggal/Desktop/Projects/GO/GO-certificate.pdf)
