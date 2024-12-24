# PHP_Exam

## DEscription :

# PHP CRUD API with RESTful Architecture

This project demonstrates the development of a RESTful API using PHP for performing CRUD operations on three independent tables: `Users`, `Products`, and `Orders`. It follows REST principles and includes detailed error handling, proper folder structure, and modular code organization.

## Features

- **CRUD Operations on Independent Tables**:
  - Users: Add a new user, Retrieve all users.
  - Products: Add a new product, Update product price.
  - Orders: Add a new order, Delete an order by ID.

- **RESTful Practices**:
  - Use of appropriate HTTP methods: `POST`, `GET`, `PUT`, `DELETE`.
  - Responses formatted in JSON.

- **Error Handling**:
  - Validation for required fields and correct input.
  - Error codes and descriptive messages for server errors and invalid operations.

- **Project Modularization**:
  - Organized folder structure for controllers, models, routes, and main entry points.

## Project Structure

- **index.php**: Main entry point to the application.
- **routes**: Contains API route definitions.
- **controllers**: Logic for handling API requests and responses.
- **models**: Database interactions for each table.
- **database**: Contains the database configuration and connection files.

## Database Design

The project uses a normalized database with three independent tables:

1. **Users Table**:
   - `id` (INT, Primary Key, Auto-increment)
   - `name` (VARCHAR)
   - `email` (VARCHAR)
   - `phone` (VARCHAR)

2. **Products Table**:
   - `id` (INT, Primary Key, Auto-increment)
   - `product_name` (VARCHAR)
   - `price` (DECIMAL)

3. **Orders Table**:
   - `id` (INT, Primary Key, Auto-increment)
   - `order_date` (DATE)
   - `status` (VARCHAR)

## APIs

### Users APIs
- **Add User** (POST `/users`): Inserts a new user.
- **Get Users** (GET `/users`): Retrieves all users.

### Products APIs
- **Add Product** (POST `/products`): Adds a new product.
- **Update Product Price** (PUT `/products/:id`): Updates the price of a product by ID.

### Orders APIs
- **Add Order** (POST `/orders`): Adds a new order.
- **Delete Order** (DELETE `/orders/:id`): Deletes an order by ID.

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

<div align="center">
 <video src="https://github.com/user-attachments/assets/089db189-2e87-485d-b3ac-906ef7dc6f83" type="video/mp4"> 
</video>
</div>
