# 🔌 API Testing — reqres.in using Postman

![API Testing](https://img.shields.io/badge/Testing-API-7C3AED?style=for-the-badge)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Status](https://img.shields.io/badge/All%20Tests-PASSED%20✅-brightgreen?style=for-the-badge)
![Test Cases](https://img.shields.io/badge/Test%20Cases-12-blue?style=for-the-badge)

## 📌 Project Overview
This project involves **manual API testing** of the [reqres.in](https://reqres.in) REST API using **Postman**.
It covers positive and negative test scenarios across Users, Authentication, and Resources modules.

---

## 📊 Test Summary

| Total TCs | Passed | Failed | Methods Covered |
|:---------:|:------:|:------:|:---------------:|
| 12 | ✅ 12 | ❌ 0 | GET, POST, PUT, DELETE |

---

## 🧪 Modules Tested

### 👤 Users Module
| TC ID | Test Case | Method | Expected | Status |
|-------|-----------|--------|----------|--------|
| TC-USR-001 | Get list of users (page 1) | GET | 200 OK | ✅ Pass |
| TC-USR-002 | Get list of users (page 2) | GET | 200 OK | ✅ Pass |
| TC-USR-003 | Get single user (valid ID) | GET | 200 OK | ✅ Pass |
| TC-USR-004 | Get single user (invalid ID) | GET | 404 Not Found | ✅ Pass |
| TC-USR-005 | Create new user | POST | 201 Created | ✅ Pass |
| TC-USR-007 | Update user | PUT | 200 OK | ✅ Pass |
| TC-USR-008 | Delete user | DELETE | 204 No Content | ✅ Pass |

### 🔐 Authentication Module
| TC ID | Test Case | Method | Expected | Status |
|-------|-----------|--------|----------|--------|
| TC-AUTH-001 | Register with valid credentials | POST | 200 OK + token | ✅ Pass |
| TC-AUTH-002 | Register without password | POST | 400 Bad Request | ✅ Pass |
| TC-AUTH-004 | Login with valid credentials | POST | 200 OK + token | ✅ Pass |
| TC-AUTH-005 | Login without password | POST | 400 Bad Request | ✅ Pass |
| TC-AUTH-006 | Login with wrong credentials | POST | 400 Bad Request | ✅ Pass |

---

## 📁 Project Files
| File | Description |
|------|-------------|
| `reqres.in API Testing.postman_collection.json` | Postman collection — import to run all tests |
| `screenshot/` | Screenshots of all test executions |

---

## 🚀 How to Run
1. Download `reqres.in API Testing.postman_collection.json`
2. Open **Postman**
3. Click **Import** → select the file
4. Click **Run collection**

---

## 🛠️ Tools Used
- **Postman** — API testing
- **reqres.in** — Test API
- **JavaScript** — Postman test scripts (pm.test)

---

## 👩‍💻 Author
**Sumaiya Noor Muna** — Junior SQA Engineer  
📧 sumaiyanoormona35292@gmail.com | [GitHub](https://github.com/sumunoor)
