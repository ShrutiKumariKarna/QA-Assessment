# QA Assessment – Swag Labs

## 📌 Overview

This repository contains my QA assessment work, where I performed manual testing, exploratory testing, security testing, regression strategy, API testing, and database testing. The goal was to evaluate the application, identify issues, and validate functionality in a simple and structured way.

---

## 📂 Project Structure

```
QA-Assessment/
├── Test-Cases/
├── Bug-Reports/
├── Postman/
├── Exploratory-Testing/
├── Security-Analysis/
├── Regression-Testing-Strategy/
├── Database-Testing/
├── Scenario-Based-Questions/
└── README.md
```

---

## 🧪 Testing Areas Covered

### 1. Test Cases

Created test cases covering major functionalities like login, product selection, cart, and checkout.

---

### 2. Bug Reports

Identified and documented multiple bugs with clear steps, expected vs actual results, and severity/priority.

---

### 3. Exploratory Testing

Performed session-based testing to find usability issues and unexpected behaviors in the application.

---

### 4. Security Testing

Checked basic security aspects like:

* Login input validation
* Password handling
* Session behavior
* Identified risks and provided recommendations

---

### 5. Regression Testing Strategy

Designed a regression approach for a new **Wishlist feature**, focusing on impacted areas and prioritizing critical flows.

---

### 6. API Testing

Performed API testing using Reqres API in Postman:

* Covered GET, POST, PUT, PATCH, DELETE
* Used environment variables for better management
* Added test scripts for validation
* Simulated authentication using login token

---

## 🗄️ Database Testing

Performed database testing on the **classicmodels MySQL database** to verify data integrity, consistency, accuracy, and CRUD operations using SQL queries.

It includes:

* Data integrity testing (Primary key, Foreign key, NULL checks, duplicates)
* CRUD operation validation (Create, Read, Update, Delete)
* Test scenarios and execution results

---

## 🔗 API Testing – Access My Work

### Option 1: View via Postman Link

👉 https://www.postman.com/shrutikarna1999-9902471/codexx-api-testing/request/51099154-2c1db880-f3d5-4b4f-8d1d-4f2063a102d8?sideView=variables

**Steps:**

1. Open the link
2. Add variables:

   * `base_url` = https://reqres.in/api
   * `api_key` = reqres_fe63f853c4a24a7bbebb1f9f15f2598d
   * `token` = QpwL5tke4Pnpja7X5
3. Run the requests

---

### Option 2: Import Files in Postman

**Files included:**

* `postman_collection.json`
* `EnvironmentSetup.postman_environment.json`

**Steps:**

1. Open Postman
2. Click **Import**
3. Upload both files
4. Select environment
5. Add variables:

   * `base_url` = https://reqres.in/api
   * `api_key` = reqres_fe63f853c4a24a7bbebb1f9f15f2598d
   * `token` = QpwL5tke4Pnpja7X5
6. Run requests from collection

---

## ✅ Key Highlights

* Focused on real user scenarios
* Clear and simple bug reporting
* Practical API testing with validation
* Database integrity and CRUD validation
* Covered both functionality and usability aspects
* Maintained clean and organized documentation

---

## 🙌 Final Note

This assessment helped me strengthen my understanding of QA processes, testing approaches, API validation, and database testing. I focused on keeping everything simple, clear, and practical.
