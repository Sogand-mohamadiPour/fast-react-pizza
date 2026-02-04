# 🍕 Fast React Pizza Co.

**Fast React Pizza Co.** is a modern Single Page Application (SPA) where users can browse a pizza menu, place orders, and track their order status in real time.

This project focuses on creating a smooth and realistic food ordering experience using React and modern frontend technologies.

---

## 🚀 Features

- 📋 **Live Menu from API**  
  Fetches pizza data from a real backend API.

- 🛒 **Shopping Cart**  
  Add, remove, and update pizzas before placing an order.

- 📦 **Place Orders**  
  Users can submit their order directly to the API.

- 🧾 **Unique Order ID**  
  Each order receives a unique ID so users can track their order later.

- 📍 **Geolocation Support**  
  The app can detect the user’s location to help with delivery details.

- 🔄 **Order Status Tracking**  
  Users can check the status of their order anytime using their order ID.

- ⚡ **Priority Order Option**  
  Even after placing an order, users can upgrade it to **priority delivery** by paying **20% extra** on the total price using a simple checkbox option.

---

## 🧠 Tech Stack

- **React** – UI development  
- **React Router** – Routing & data loading  
- **Redux** – State management (cart, order data, etc.)  
- **Tailwind CSS** – Styling  
- **Render-as-you-fetch (React Router loaders)** – Data fetching before rendering routes  
- **REST API** – For menu data and order submission  

---
## 🚀 Live Demo
  👉 https://fast-react-pizza-sigma-snowy.vercel.app
  
---

## 🖥️ How It Works

1. The app loads the **pizza menu** from an external API.  
2. Users add pizzas to their **cart**.  
3. During checkout, the user provides delivery details (with optional geolocation).  
4. The order is **sent back to the API**.  
5. The API returns a **unique order ID**.  
6. Users can use this ID on the tracking page to **check their order status**.
7. At any time, users can mark their order as **priority**, increasing the total price by **20%** for faster delivery.

---

## 🛠️ Getting Started

```bash
npm install
npm run dev
```
then open: 
http://localhost:5173

---

## 📌 Learning Goals
This project was built to practice:

- Advanced React patterns
- State management with Redux
- Real-world routing and data loading
- API integration
- Building a complete user flow (browse → cart → order → track)


