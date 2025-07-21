# 🛒 Ulta Beauty Price Tracker

A **Python automation project** that tracks the prices of skincare products from **Ulta Beauty** and sends **email alerts when the total price drops below a specified budget**.

---

## 📌 Overview

This project solves a common problem:  
**Manually checking skincare product prices every day is time-consuming.**

With this script, you can:

- Automatically track product prices.
- Log the daily data into a CSV file.
- Receive an email alert when prices fall below your set budget.

---

## 🚀 Features

- **Web Scraping** – Extracts product prices from Ulta Beauty using **BeautifulSoup**.
- **Automated Email Alerts** – Sends an email when the combined price is within budget.
- **Scheduled Execution** – Automatically runs **every 12 hours**.

---

## 🛍️ Products Tracked

1. **COSRX Advanced Snail 96 Mucin Power Essence**  
2. **Anua Heartleaf Quercetinol Pore Deep Cleansing Foam**  
3. **Skin1004 Madagascar Centella Ampoule**

---

## ⚙️ How It Works

1. The script scrapes product prices from Ulta Beauty.
2. Daily prices are saved to a **CSV file**.
3. If the total price is below **$70**, an **email notification** is sent.
4. The process repeats every **12 hours**.

---

## 🧰 Tech Stack

- **Python 3**
- `BeautifulSoup` – Web scraping  
- `Requests` – HTTP requests  
- `Pandas` – Data handling and CSV  
- `smtplib` – Sending emails  
- `datetime`, `time` – System utilities

---

## Contact
If you have any questions or feedback, feel free to reach out:
### Prachi Holkar
Linkedin URL: https://www.linkedin.com/in/prachi-holkar/ | 
Email: holkarprachi@hotmail.com
