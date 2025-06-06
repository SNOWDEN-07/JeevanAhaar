# JeevanAhaar 🍱

**JeevanAhaar** is a real-time Android and Web-based application designed to connect food donors — such as restaurants, grocery stores, and individuals — with charities and NGOs. The goal is to reduce food waste and promote food security by ensuring surplus edible food reaches people in need.

## 🌟 Features

### ✅ For Donors:
- 📦 Easy donation form submission
- 🕒 Real-time pickup scheduling
- 📍 Live location tracking for pickups
- 📊 Donation history and analytics

### ✅ For Charities:
- 🔔 Real-time donation notifications
- 📌 Interactive map to view available food donations
- 📅 Pickup scheduling system

### ✅ For Admin:
- 🧑‍💼 Manage users and donation requests
- 📈 View platform-wide analytics and donation impact
- 📬 Send broadcast notifications and updates

---

## 🛠️ Tech Stack

| Layer            | Tech Used                     |
|------------------|-------------------------------|
| Frontend (Web)   | HTML, CSS, JavaScript         |
| Frontend (Android) | Java, Android Studio          |
| Backend          | Node.js / Java Spring Boot (choose based on implementation) |
| Database         | MySQL / Firebase Realtime DB  |
| Authentication   | Firebase Auth / JWT           |
| APIs             | Google Maps API, Firebase Cloud Messaging |

---

## 📱 Screenshots

> *Add relevant screenshots of your app's UI here for better visualization.*

---

## 🗃️ Database Schema (Example)

- **Users**
  - `user_id`, `name`, `email`, `role` (donor/charity/admin), `location`

- **Donations**
  - `donation_id`, `user_id`, `food_type`, `quantity`, `expiry_time`, `pickup_status`, `timestamp`

- **Pickups**
  - `pickup_id`, `donation_id`, `charity_id`, `scheduled_time`, `status`

---

## 🚀 Getting Started

### 🖥️ Web App
```bash
git clone https://github.com/YOUR_USERNAME/jeevanahaar.git
cd jeevanahaar
npm install
npm start
