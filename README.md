# Inventory & Order Management System

##  Overview

This is a full-stack Inventory & Order Management System built to manage products, customers, and orders with proper inventory tracking and business logic.

---

##  Tech Stack

### Backend

* Python (FastAPI)
* SQLAlchemy
* SQLite (for local testing)

### Frontend

* React (Create React App)

### Database

* SQLite (local)
* PostgreSQL (planned for production)

---

## Features Implemented

### Product Management

* Create product
* View all products
* Update product
* Delete product

### Customer Management

* Create customer
* View customers
* Delete customer

### Order Management

* Create order
* View orders
* Delete order

---

## Business Logic Implemented

* Unique SKU for products
* Unique email for customers
* Prevent negative inventory
* Prevent orders if stock is insufficient
* Auto-reduce stock after order
* Automatic total calculation

---

## Frontend Status

* React app initialized
* Product listing integrated with backend API
* Basic UI for displaying products

---

## Backend Status

* All APIs implemented and tested via Swagger UI
* Backend running successfully locally

---

## How to Run Locally

### Backend

```bash
cd backend
uvicorn app.main:app --reload
```

Open:
http://127.0.0.1:8000/docs

---

### Frontend

```bash
cd frontend
npm install
npm start
```

Open:
http://localhost:3000

---

## Deployment Status

Deployment was attempted using platforms like Render and Railway.

However, due to environment compatibility issues (Python version and dependency build issues), deployment could not be completed within the given timeframe.

The application is fully functional and tested locally.

---

## Future Improvements

* Complete frontend UI (forms, dashboard)
* Deploy backend and frontend
* Add authentication
* Improve UI/UX

---

## Conclusion

The system successfully demonstrates full-stack integration with working backend APIs and a connected frontend interface. Core business logic and functionalities have been implemented as required.
