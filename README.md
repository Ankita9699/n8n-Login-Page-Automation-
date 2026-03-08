# n8n-Login-Page-Automation

An automation project built with **n8n** to test and validate a login page workflow.  
This project demonstrates how to use **n8n**, **HTTP Request**, and optional **Python/Selenium** integration for login page automation, response validation, and reporting.

---

## 📌 Project Overview

This project is designed to automate login page testing in a simple and reusable way.

It can be used for:

- Login API testing
- End-to-end login workflow validation
- Response status verification
- CI/CD pipeline integration
- QA automation portfolio showcase

---

## 🚀 Features

- Automates login page request flow
- Supports username and password input handling
- Validates successful and failed login scenarios
- Can be triggered manually, by webhook, or through CI/CD
- Easy to integrate with Python, Selenium, or Playwright
- Can send alerts or reports after execution

---

## 🛠️ Tech Stack

- **n8n**
- **HTTP Request Node**
- **Webhook Node**
- **IF Node**
- **Set Node**
- **Python** *(optional)*
- **Selenium / Playwright** *(optional for UI automation)*
- **GitHub Actions / Jenkins** *(optional for CI/CD)*

---

## 📂 Project Structure

```bash
n8n-Login-Page-Automation/
│
├── workflows/
│   └── login-workflow.json
│
├── scripts/
│   └── login_test.py
│
├── screenshots/
│   └── login-test-result.png
│
└── README.md
