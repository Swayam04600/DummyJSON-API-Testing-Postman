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

<img width="1375" height="800" alt="Token Store Automitacally- 1" src="https://github.com/user-attachments/assets/edfbfc0a-94df-47c7-b598-de2d2718f307" />

<img width="1380" height="366" alt="Token Stored Automatically- 2" src="https://github.com/user-attachments/assets/ab3d4dac-f12e-44c1-a68f-5354656f11a2" />

<img width="1389" height="503" alt="Authorization" src="https://github.com/user-attachments/assets/0cd10240-5002-4b33-8081-c11f5dcf54f9" />


<img width="752" height="432" alt="Authorization- 2" src="https://github.com/user-attachments/assets/7d650b79-4293-4b3d-b554-9fa11089e583" />


---

## 🌐 Environment Configuration

Base URL and token handled using Postman environment variables.

<img width="1385" height="343" alt="Environment Variables" src="https://github.com/user-attachments/assets/38d2a4b7-25cf-4927-acab-e3832da44439" />


---

## 📥 GET Requests (Data Retrieval)

Fetching records from the backend server.

<img width="752" height="320" alt="Get Post" src="https://github.com/user-attachments/assets/b798a813-3e68-4c1d-bbc4-604f6a088284" />

---

## ✔️ Response Validation (Assertions)

Automated test scripts verifying response status and data.

<img width="752" height="420" alt="Get Single Post Test" src="https://github.com/user-attachments/assets/f455b549-c97a-4d99-beda-aadcecba357f" />


---

## ➕ Create Resource (POST)

Creating a new resource via API.

<img width="752" height="318" alt="Create Post" src="https://github.com/user-attachments/assets/338b8d03-33f2-422a-9940-ec313b96edc8" />

---

## ✏️ Update Resource (PUT/PATCH)

Updating server data.

<img width="752" height="421" alt="Update Post" src="https://github.com/user-attachments/assets/1fceebf0-3b22-4aa7-a794-b9dd8093ff7f" />

---

## ❌ Delete Resource (DELETE)

Deleting a record from backend.

<img width="752" height="342" alt="Delete Post" src="https://github.com/user-attachments/assets/eb8435ef-f219-4f4d-9228-5002b10538f0" />

---

## 🚫 Negative Testing

Login with invalid credentials and validation of error response.

<img width="752" height="314" alt="Negative Login Password" src="https://github.com/user-attachments/assets/913f3d08-d063-4adc-acbd-fbccc7f23e1b" />


---

## 🧱 Schema Validation

Verification of response JSON structure.

<img width="752" height="332" alt="Schema Validation" src="https://github.com/user-attachments/assets/e011611a-ec36-4621-906b-5539e89d80ad" />


---

## 🔒 Security Testing

Unauthorized access blocked (401 response).

<img width="752" height="373" alt="Security 1" src="https://github.com/user-attachments/assets/3abcccee-4496-4afe-b361-48e36dce3eb5" />

<img width="752" height="314" alt="Security 2" src="https://github.com/user-attachments/assets/7f0c0741-ea94-4d11-986c-3d02c959d531" />


---

## ⚠️ Edge Case Testing

Testing non-existing resources (404 response).

<img width="752" height="314" alt="Edge Case" src="https://github.com/user-attachments/assets/9080da2e-a635-4bb2-b134-3277823dd751" />


---

## ▶️ Collection Runner (Automation Execution)

Execution of complete API suite using Postman Runner.

<img width="752" height="441" alt="Collection Runner 1" src="https://github.com/user-attachments/assets/ed3197df-84a9-4c0b-9460-71021985e8a6" />

<img width="752" height="422" alt="Collection Runner 2" src="https://github.com/user-attachments/assets/220116dc-af2a-4ef6-94c4-0e0ef225f9c2" />


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
