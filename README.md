# 🛍️ E-Commerce API Testing with Postman

## 📌 Project Overview

This project demonstrates REST API testing for an E-Commerce application using **Postman**. It focuses on user authentication, retrieving user information, and accessing product data. The project validates API responses, status codes, request parameters, and endpoint functionality.

---

## 🛠️ Tools & Technologies

* Postman
* REST API
* JSON
* Git & GitHub

---

## 🚀 Features Tested

* User Login Authentication
* Get User Profile
* Get All Products
* Get Single Product by ID
* Dynamic Product ID Handling
* Response Validation
* HTTP Status Code Validation

---

## 📂 API Endpoints Covered

| Method | Endpoint         | Description                                       |
| ------ | ---------------- | ------------------------------------------------- |
| POST   | `/login`         | Authenticate user and receive an access token     |
| GET    | `/user/profile`  | Retrieve authenticated user's profile             |
| GET    | `/products`      | Retrieve all available products                   |
| GET    | `/products/{id}` | Retrieve details of a single product using its ID |

---

## ✅ Test Scenarios

* Verify successful login with valid credentials.
* Validate authentication token generation.
* Retrieve authenticated user's profile.
* Fetch all available products.
* Extract and use a product ID dynamically.
* Retrieve product details using the extracted product ID.
* Validate response body, response time, and HTTP status codes.
* Test invalid requests and error responses.

---

## 📥 How to Run

1. Clone this repository.
2. Import the Postman Collection into Postman.
3. Configure environment variables if required.
4. Execute the **Login** request to generate an authentication token.
5. Run the remaining requests individually or use the Collection Runner to execute the complete workflow.

---

