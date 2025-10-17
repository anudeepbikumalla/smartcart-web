# SmartCart Store 🛒

SmartCart Store is a lightweight, modular e-commerce web application built using **vanilla JavaScript**, **HTML**, and **CSS**.  
It simulates core shopping workflows like product browsing, cart management, and checkout, designed for learning and performance optimization.

---

## ⚙️ Core Functionalities

### 🛍️ Product Management
- Dynamically renders products using JavaScript data objects.
- Supports OOP models (`Product`, `Clothing` classes) for extendable product logic.
- Displays ratings, prices, and attributes dynamically from source data.

### 🛒 Cart System
- Add or remove products with quantity tracking.
- Persists cart state using `localStorage`.
- Automatically recalculates totals and updates cart count in real-time.

### 💸 Pricing & Delivery
- Computes subtotal, taxes, and delivery charges dynamically.
- Formats values consistently through a central `money.js` utility.
- Includes delivery-date estimation logic.

### 📦 Checkout Flow
- Updates item quantities and order totals instantly.
- Displays payment and order summaries with clear structure.

### 📱 Responsive Design
- Uses CSS Grid and Flexbox for layout.
- Automatically adjusts product grid columns for any screen size.
- Fixed top navigation bar for consistent UX.

---

## 🧠 Tech Stack
- **HTML5**
- **CSS3** (Grid, Flexbox, Media Queries)
- **JavaScript (ES6 Modules)**
- **LocalStorage API**

---

## 🌐 Live Demo
https://smartcartjs.netlify.app/

---

## 🧩 Purpose
SmartCart demonstrates how full e-commerce functionality can be achieved **without frameworks** — focusing purely on modular JavaScript, DOM manipulation, and clean component separation.

---



