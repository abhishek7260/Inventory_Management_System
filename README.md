# Inventory Management System

An **ASP.NET MVC 5** web application for managing products, customers, and orders with role-based authentication, Entity Framework integration, and user-friendly dashboards.

---

## 📂 Project Structure
- **Controllers/** – Handles application logic (e.g., `AccountController`, `ProductController`).
- **Models/** – Entity classes representing database tables (e.g., `Customer`, `Order`, `Cart`).
- **Views/** – Razor views for UI (`Account`, `Dashboard`, `Product`, etc.).
- **DAL/** – Data Access Layer with repository classes (e.g., `productRepo`, `orderRepo`).
- **Services/** – Business logic services (`SearchProductByCategory`, `checkOut`, etc.).
- **ViewModels/** – Strongly typed classes for passing structured data to views.
- **Migrations/** – Entity Framework Code-First migrations for database schema.
- **Content/** – CSS, images, and static content.
- **Scripts/** – JavaScript and libraries.

---

## 🚀 Features
- **Authentication & Authorization**  
  - User login, signup, password reset.  
  - Role-based access (e.g., Admin, Customer).  

- **Product Management**  
  - Add, update, delete products.  
  - Search products by category.  

- **Customer Management**  
  - Register and manage customers.  
  - Customer dashboard with order history.  

- **Cart & Checkout**  
  - Add items to cart.  
  - Checkout process with order placement.  

- **Order Management**  
  - View and manage orders.  
  - Track order details.  

- **Forgot & Reset Password**  
  - Custom password reset implementation with token validation.  

---

## 🛠️ Technologies Used
- **ASP.NET MVC 5** (C#)  
- **Entity Framework (Code First + Migrations)**  
- **SQL Server** (for database)  

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/InventoryManagement.git
   cd InventoryManagement
