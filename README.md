# 🌱 Paradise Nursery Shopping Application

Welcome to **Paradise Nursery**, an online shopping application for plant lovers where green meets serenity!

---

## 📌 Project Overview

**Paradise Nursery** is a dynamic e-commerce web application built with **React**, **Redux Toolkit**, and **Vite**. The application allows users to:
- Browse a curated collection of houseplants categorized by their benefits (Air Purifying, Aromatic & Fragrant, Insect Repellent, Medicinal, Low Maintenance).
- View plant details including name, thumbnail image, description, and price.
- Add plants to a global shopping cart with dynamic item quantity badges.
- Manage shopping cart items (increment, decrement, remove).
- Calculate real-time subtotal per plant and overall total cart cost.
- Seamless navigation between the Landing Page, Product Catalog, and Cart views.

---

## 🚀 Features

- **Landing Page:** Beautiful greenhouse backdrop with company mission statement and a "Get Started" call-to-action button.
- **Responsive Navigation Bar:** Persistent navigation displaying company branding, links to Home, Plants, and an interactive Cart icon with a real-time badge indicator.
- **Categorized Plant Catalog:** Houseplants grouped into distinct categories with at least 6 unique plants per category.
- **Smart "Add to Cart":** Disables button and changes label to "Added to Cart" once an item is added to prevent accidental duplicates.
- **Full Shopping Cart Management:**
  - Dynamic total cart cost calculation.
  - Item subtotal calculation `(Unit Price × Quantity)`.
  - Increment (`+`) and decrement (`-`) quantity controls (auto-removes item when quantity reaches zero).
  - One-click item removal with "Delete" button.
  - "Continue Shopping" button returning to plant catalog.
  - "Checkout" button providing instant feedback ("Coming Soon").

---

## 🛠️ Tech Stack

- **React 18** (Functional components, hooks: `useState`, `useEffect`)
- **Redux Toolkit** (Global state management for cart items)
- **React-Redux** (`useSelector`, `useDispatch`)
- **Vite** (Next-generation front-end build tool)
- **CSS3** (Responsive design, animations, glassmorphism)

---

## 📂 Project Structure

```
e-plantShopping/
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.css
│   ├── AboutUs.jsx          # Company background and mission
│   ├── App.css              # Landing page styles and background image
│   ├── App.jsx              # Main app component with landing page
│   ├── CartItem.css         # Shopping cart styling
│   ├── CartItem.jsx         # Shopping cart component and item management
│   ├── CartSlice.jsx        # Redux slice for cart actions and state
│   ├── ProductList.css      # Product catalog grid styles
│   ├── ProductList.jsx      # Plant listing with categories & cart controls
│   ├── index.css
│   ├── main.jsx             # React entry point with Redux Provider
│   └── store.js             # Redux store configuration
├── index.html
├── package.json
└── README.md
```

---

## 💻 Installation & Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mohdfaisalsorathia/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

---

## 👤 Author

**Mohd Faisal Sorathia**
- GitHub: [@mohdfaisalsorathia](https://github.com/mohdfaisalsorathia)

---

## 📄 License

This project is licensed under the Apache License 2.0.