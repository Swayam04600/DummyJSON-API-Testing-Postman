# DummyJSON E-commerce Backend API Testing (Postman)

## 📌 Project Overview

This project demonstrates **end-to-end REST API testing** of an e-commerce backend using Postman.

The goal of the project is to simulate the real responsibilities of a **QA / Backend Tester** including authentication handling, request chaining, CRUD validation, automated assertions, and execution of a full API test suite.

The APIs are tested against the public **DummyJSON REST service**.

---

## 🧰 Tools & Technologies

* Postman
* REST API
* JavaScript (Postman Test Scripts)
* JSON
* GitHub

---

## 🧪 Testing Areas Covered

* Environment variables & parameterization
* Authentication (JWT token handling)
* Authorization testing (protected endpoints)
* CRUD Operations (Create, Read, Update, Delete)
* Automated response validation
* Status code verification
* Negative testing
* Edge case testing
* Security testing
* JSON Schema validation
* Request chaining (dynamic data passing)
* Collection Runner execution (automation)

---

## 🔐 Authentication Testing

Login using valid credentials and capture access token.

![Login Success](screenshots/02_login_success.png)

---

## 🔑 Token Handling & Authorization

Token dynamically saved into environment and used to access protected endpoint `/auth/me`.

![Token Script](screenshots/03_token_capture_script.png)

![Authorized User](screenshots/04_authorized_user.png)

---

## 🌐 Environment Configuration

Base URL and token handled using Postman environment variables.

![Environment Variables](screenshots/01_environment_variables.png)

---

## 📥 GET Requests (Data Retrieval)

Fetching records from the backend server.

![Get Posts](screenshots/05_get_posts.png)

---

## ✔️ Response Validation (Assertions)

Automated test scripts verifying response status and data.

![Assertions](screenshots/06_get_single_post_tests.png)

---

## ➕ Create Resource (POST)

Creating a new resource via API.

![Create Post](screenshots/07_create_post.png)

---

## ✏️ Update Resource (PUT/PATCH)

Updating server data.

![Update Post](screenshots/08_update_post.png)

---

## ❌ Delete Resource (DELETE)

Deleting a record from backend.

![Delete Post](screenshots/09_delete_post.png)

---

## 🚫 Negative Testing

Login with invalid credentials and validation of error response.

![Negative Login](screenshots/10_negative_login.png)

---

## 🧱 Schema Validation

Verification of response JSON structure.

![Schema Validation](screenshots/11_schema_validation.png)

---

## 🔒 Security Testing

Unauthorized access blocked (401 response).

![Unauthorized Access](screenshots/12_security_unauthorized.png)

---

## ⚠️ Edge Case Testing

Testing non-existing resources (404 response).

![Edge Case](screenshots/13_edge_case_404.png)

---

## ▶️ Collection Runner (Automation Execution)

Execution of complete API suite using Postman Runner.

![Collection Runner](screenshots/14_collection_runner.png)

---

## 🚀 How to Run the Project

1. Clone or download this repository
2. Import `collection.json` into Postman
3. Import `environment.json`
4. Select the environment in Postman
5. Run the **Login request** first
6. Run the complete collection using **Collection Runner**

---

## 📚 Learning Outcomes

Through this project I learned:

* Real-world API testing workflow
* Handling authorization tokens
* Writing automated API test scripts
* Using environment variables and dynamic data
* Backend validation and error handling
* Running automated API test suites

---

## 👨‍💻 Author

**Swayam Uniyal**

Aspiring QA Engineer | API Testing | Manual Testing | Automation (Learning)
