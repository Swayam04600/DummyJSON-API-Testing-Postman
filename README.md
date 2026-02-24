# DummyJSON E-commerce API Testing (Postman)

## Project Overview

This project demonstrates end-to-end REST API testing of a real-world e-commerce backend using Postman.

The objective of this project is to simulate the responsibilities of a QA Engineer performing backend testing including authentication handling, CRUD validation, and automated test scripting.

---

## Tools Used

* Postman
* JavaScript (Postman scripting)
* REST APIs
* GitHub

---

## Features Covered

* Environment variables
* Authentication (JWT token handling)
* Automated test validations
* Response assertions
* CRUD operations testing
* Status code validation
* Chained requests (dynamic data passing)

---

## Test Scenarios

### Authentication

* Login using valid credentials
* Capture JWT token
* Access protected endpoint (/auth/me)

### Product APIs

* Get all products
* Get single product
* Create new product
* Update product
* Delete product

### Automated Validations

* Status code checks
* Response body validation
* JSON schema checks
* Dynamic variable storage

---

## How to Run

1. Import `collection.json` into Postman
2. Import `environment.json`
3. Select the environment
4. Run Login request first
5. Run the full collection

---

## Learning Outcome

Through this project I learned:

* Real API testing workflow
* Handling authorization tokens
* Writing automated API tests
* Using variables and environments
* Test data chaining between requests

---

## Author

Swayam Uniyal
