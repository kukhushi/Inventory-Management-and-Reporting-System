# Inventory-Management-and-Reporting-System
# Inventory Management and Reporting System

The **Inventory Management and Reporting System** is a layered enterprise application developed to manage inventory operations efficiently and generate reports for better decision-making.

This project follows a **4-layer architecture** for modularity and maintainability.

---

## Project Architecture

### 1. Presentation Layer

Developed using **React.js**, this layer provides the user interface for managing inventory and viewing reports.

**Folder:** `frontend/`

---

### 2. Authentication Layer

Responsible for:

* User login
* Registration
* Access validation
* Security control

**Folder:** `authentication/`

---

### 3. Business Layer

Contains:

* Inventory processing logic
* Report generation logic
* Business validations

**Folder:** `business/`

---

### 4. Database Layer

Handles:

* MySQL database schema
* SQL scripts
* Data storage operations

**Folder:** `database/`

---

## Technologies Used

* **Frontend:** React.js
* **Backend:** Spring Boot / Java
* **Database:** MySQL
* **Version Control:** Git and GitHub

---

## Features

* Inventory Tracking
* Stock Management
* Report Generation
* Authentication and Authorization
* Layered Architecture Implementation

---

## How to Run

### Frontend

```bash id="kg8lwb"
cd frontend
npm install
npm start
```

### Backend

```bash id="ehxg03"
cd backend
mvn spring-boot:run
```

### Database

Import SQL scripts from the `database/` folder into MySQL.

---

## Author

**Khushi Kumari**
