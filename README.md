# Inventory Management System

## Tech Stack
- Backend: Spring Boot (Java)
- Frontend: React (JavaScript)
- Database: MySQL

## Setup Instructions

### Prerequisites
- Java 17
- Node.js
- MySQL

### Backend Setup
1. Navigate to the `backend` directory.
2. Configure MySQL database in `src/main/resources/application.properties`.
3. Run the Spring Boot application:
   ```
   mvn spring-boot:run
   ```
   The backend will run on `http://localhost:8080`.

### Frontend Setup
1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the React application:
   ```
   npm start
   ```
   The frontend will run on `http://localhost:3000`.

### Database Setup
1. Create a MySQL database named `inventory_db`.
2. Update the database credentials in `backend/src/main/resources/application.properties`.

## API Endpoints
- POST /api/login - User login
- GET /api/products - Get all products
- POST /api/products - Add a new product
- PUT /api/products/{id} - Update a product
- DELETE /api/products/{id} - Delete a product
- PATCH /api/products/{id}/stock/{qty} - Update product stock
- GET /api/products/low-stock - Get low stock products

## Features
- User authentication
- Product CRUD operations
- Stock management
- Low stock warnings
- Responsive UI

## Screenshots
Screenshots are stored in the `screenshots` directory.
