# Retail Inventory & Stock Management API

A lightweight RESTful API and visual dashboard built with **Python (Flask)** and **SQLite**, designed for real-time inventory tracking, stock alerts, and catalog management for retail systems.

---

## 🚀 Key Features

* **Live Dashboard Interface:** Branded ShopriteX visual dashboard with real-time stock counters and low-stock indicators.
* **REST API Endpoints:** JSON endpoints for full catalog retrieval and automated stock monitoring.
* **SQLite Database:** Persistent storage for inventory items, categories, pricing, and quantities.
* **Automated Low-Stock Alerts:** Highlights items falling below minimum thresholds (< 10 units).

---

## 🛠️ Tech Stack

* **Backend:** Python 3, Flask, Flask-SQLAlchemy
* **Database:** SQLite
* **Frontend:** HTML5, CSS3, Bootstrap 5
* **Version Control:** Git & GitHub

---

## 📡 API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/` | Renders the ShopriteX visual dashboard |
| `GET` | `/products` | Returns JSON array of all inventory products |
| `GET` | `/low-stock` | Returns JSON array of products with stock < 10 |

---

## 🎓 Disclaimer
*This project is an independent educational demonstration built for portfolio purposes and is not directly affiliated with or endorsed by Shoprite Group.*
