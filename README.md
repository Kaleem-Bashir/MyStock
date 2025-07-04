# 📊 Real-Time Stock Tracker App

A full-stack real-time stock tracker built with **React**, **Tailwind CSS**, and **Firebase**. This app allows users to sign in, search for stocks, view real-time (mock) stock data, and manage a watchlist.

---

## 🚀 Features

- 🔐 Firebase Authentication (Email/Password)
- 📂 Firestore for storing watchlists
- 🔍 Search & filter stocks
- 📈 Mock stock data with real-time-ready structure
- 🧩 Component-based architecture
- 🗂 Page routing (Home, Watchlist, Login)
- 🎨 Styled with Tailwind CSS

---

## 🖼️ Screenshots

📌 Here are some example screenshots of the app in action:

### 📍 Home Page
![Home Page](https://www.imag-r.com/static/uploads/Screenshot_2025-06-30_2339351518__extra.png?random=%3F1751656560)

### 📊 Stock Graph
![Graph](https://www.imag-r.com/static/uploads/Screenshot_2025-06-30_2336430939__extra.png?random=%3F1751656196)

### 🕰️ Historical Data View
![History Data](https://www.imag-r.com/images/display/Screenshot_2025-07-01_0110112132__extra.png)



---

## 🛠️ Tech Stack

| Technology       | Purpose                              |
|------------------|---------------------------------------|
| React            | Frontend framework                    |
| Tailwind CSS     | Utility-first styling                 |
| Firebase Auth    | User authentication (Email/password)  |
| Firebase Firestore | Real-time NoSQL database           |
| React Router DOM | Page routing                          |

---

## 📁 Folder Structure
/src
│
├── /components
│ ├── Header.jsx
│ ├── SearchBar.jsx
│ ├── StockList.jsx
│ └── Watchlist.jsx
│
├── /pages
│ ├── Home.jsx
│ ├── Watchlist.jsx
│ └── Login.jsx
│
├── /services
│ └── firebase.js
│
├── App.jsx
├── index.js
└── main.css (Tailwind base)
