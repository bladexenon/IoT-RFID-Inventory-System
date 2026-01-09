# IoT RFID Inventory & Asset Tracking System

**Role:** Data Engineer Intern (Team of 6)  
**Personal contributions:**  
- Designed the **frontend dashboard** for monitoring IT lab equipment, including real-time inventory, borrow/return workflow, and RFID scan tracking  
- Developed backend logic to process **manual RFID scans** and log borrow/return events in a MySQL database with timestamps  
- Architected and maintained **relational database tables** for assets, users (anyone with an RFID), and transaction history  
- Integrated frontend, backend, and database into a fully functional system for tracking IT assets and user interactions  

**Tech Stack:** Python, MySQL, HTML, CSS, JavaScript, RFID hardware

---

## Project Overview
This system automates tracking of IT lab equipment (laptops, mice, RJ45 cables, etc.) for any user with an RFID tag. When an asset or RFID tag is scanned, the system allows the administrator to log borrowed items, track timestamps for borrowing and returning, and check inventory in real-time. A full history of transactions is maintained per asset and per RFID, giving admins complete visibility of usage.

---

## Features
- Manual RFID scan input via the frontend “Reader / Fetch ID” tab  
- Backend processes IDs and logs **borrow/return events with timestamps**  
- Relational database storing **assets, users, and full transaction history**  
- Frontend dashboard to monitor **current inventory, quantity per item, and scan history**  
- Ability to track **which items each RFID has borrowed or returned**  
- Secure login system with **role-based access** (admin / user)  

---

## How to Run (Optional)
1. Clone the repo:  
   ```bash
   git clone https://github.com/yourusername/IoT-RFID-Inventory-System.git
