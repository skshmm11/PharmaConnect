# 🧬 PharmaConnect — Real-Time Medicine Availability Platform

PharmaConnect is a full-stack web application that bridges the gap between 
patients and local pharmacies. Instead of visiting multiple stores to find 
a medicine, users can search in real-time, check stock availability at nearby 
pharmacies, and reserve medicines instantly.

## 🚀 Features

### For Patients
- 🔍 Real-time medicine search across nearby pharmacies
- 📍 GPS-based location to show nearest pharmacies first
- 🛒 Order medicines with home delivery (where available)
- 📞 Contact pharmacy directly or get directions
- ⏰ Refill reminders based on medicine type
- 📦 Order history and status tracking

### For Doctors & Pharmacy Owners
- 🏥 Dedicated stock management portal
- 📷 Barcode scanner to add medicines instantly
- ⚠️ Automatic expiry date alerts and low stock warnings
- 📋 Real-time order dashboard with status updates
- 🗂️ Full inventory management with batch and Rx tracking

## 🛠️ Tech Stack
- **Frontend** — HTML, CSS, JavaScript
- **Backend** — Python Flask
- **Database** — MongoDB
- **Auth** — JWT + bcrypt
- **Location** — OpenStreetMap (no API key needed)

## 👥 User Roles
- **Regular User** — Search, order, track medicines
- **Pharmacy Owner** — Manage stock, fulfill orders
- **Doctor** — Access stock portal and patient orders

## ⚙️ Setup
1. Install Python and MongoDB
2. Run `pip install -r requirements.txt`
3. Run `python seed.py` to load sample data
4. Run `python app.py` to start the server
5. Open `login.html` with Live Server

## 🔑 Demo Credentials
| Role | ID | Password |
|---|---|---|
| Regular User | user1 | password123 |
| Pharmacy Owner | PHR001 | password123 |
| Doctor | DOC001 | password123 |
