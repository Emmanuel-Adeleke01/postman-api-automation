# Fake Store API – Postman CLI Automation

## 📌 Project Overview

This project demonstrates API testing and automation using **Postman** and **Postman CLI**, with continuous integration through **GitHub Actions**.

The **Fake Store API** was tested across Authentication, Users, and Products endpoints. The test suite contains automated assertions covering response status codes, response structures, required fields, and data validation.

The collection was executed locally using Postman CLI and automatically through GitHub Actions.

---

## 🛠️ Tools & Technologies

- Postman
- Postman CLI
- JavaScript
- Git & GitHub
- GitHub Actions
- REST API
- JSON

---

## 🔍 API Test Coverage

### Authentication

- Login
- Validate successful authentication
- Validate authentication token
- Verify token is returned as a non-empty string

### Users

- Get all users
- Get a single user
- Add a new user
- Update a user
- Delete a user

### Products

- Get all products
- Add a new product
- Get a single product
- Add a new product
- Update a product
- Delete a product

---

## 🧪 Automated Test Results

| Metric | Result |
|---|---:|
| Requests | 11 |
| Test Scripts | 11 |
| Assertions | 44 |
| Failed Assertions | 0 |
| Pass Rate | 100% |

### Result

**44/44 assertions passed successfully.**

The collection was executed successfully using Postman CLI from the VS Code terminal and through GitHub Actions.

---

## ⚙️ Postman CLI Execution

The collection can be executed from the terminal using Postman CLI.

Example:

```bash
postman collection run "<COLLECTION_ID>" \
  -e "<ENVIRONMENT_ID>" \
  --env-var "singleUserId=1" \
  --env-var "singleProductId=1"