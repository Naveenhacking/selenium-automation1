# 🚗 Simple Login Automation Using Selenium (BMW Style)

![BMW Automation]()

## 📌 Overview

This project demonstrates how to automate a simple login form using **Python** and **Selenium WebDriver**.

It simulates a user opening a web page, entering a **username** and **password**, and clicking the **Login** button — all automatically inside a Chrome browser window.

> 🧠 This is done using a **local HTML file** (not a real website), so it’s completely safe and self-contained.

> ⚠️ **Disclaimer:** This project is for educational purposes only. Do not use Selenium to interact with real websites without permission.

---

## 💡 What This Project Does

- 🚀 Launches Google Chrome
- 🖥 Loads a local HTML login page (`selenium.html`)
- ⌨️ Enters:
  - Username: `admin`
  - Password: `1234`
- 🖱 Clicks the login button
- 🪟 Keeps the browser window open (for visibility)

---

## 📂 Files in This Project

| File           | Description                          |
|----------------|--------------------------------------|
| `main.py`      | Python script that runs automation   |
| `selenium.html`| A basic HTML login form              |
| `README.md`    | Project documentation                |

---

## 🛠 Requirements

### 💻 Software

- Python 3.x
- Google Chrome browser
- ChromeDriver (same version as Chrome)

### 📦 Python Package

Install Selenium using pip:

```bash
pip install selenium
