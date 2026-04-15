# 🛒 Amazon E-Commerce Clone

A responsive front-end web application that replicates the core shopping experience of Amazon. Built with Vanilla JavaScript, HTML5, and CSS3, this project demonstrates dynamic DOM manipulation, modular JavaScript architecture, and responsive UI design.

---

## ✨ Features

* **Dynamic Storefront** – Products are rendered dynamically using JavaScript
* **Shopping Cart Management** – Add items, update quantities, and calculate totals
* **Order History** – View past orders with IDs, dates, and pricing
* **Package Tracking** – Visual progress bar for delivery status
* **Responsive Design** – Optimized for mobile, tablet, and desktop

---

## 📂 Project Architecture

The application consists of multiple HTML views supported by modular CSS and JavaScript.

### 🔹 Main Pages

#### `amazon.html` (Storefront)

* Landing page with product listings and navigation
* Dynamically renders products using JavaScript

#### `checkout.html` (Cart & Review)

* Displays selected items and payment summary
* Dynamically updates totals and cart items

#### `orders.html` (Order History)

* Shows previous orders with details and actions
* Uses CSS Grid and Flexbox for layout

#### `tracking.html` (Delivery Status)

* Tracks order progress (Preparing → Shipped → Delivered)
* Uses URL parameters to fetch order details

---

### 📁 Folder Structure

* **`/styles`** – CSS files (global + page-specific)
* **`/scripts`** – JavaScript modules (logic & state management)
* **`/images`** – Assets and product images

---

## 💻 Getting Started

### 📌 Prerequisites

* Modern browser (Chrome, Firefox, Edge, Safari)
* Local server (required for ES Modules)

---

## 🚀 Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/amazon-project.git
cd amazon-project
```

### 2. Run Local Server

#### Method A: VS Code (Recommended)

* Open project in VS Code
* Install Live Server extension
* Right-click `amazon.html` → Open with Live Server

#### Method B: Node.js

```bash
npx http-server .
```

#### Method C: Python

```bash
python -m http.server 8000
```

Then open: **[http://localhost:8000](http://localhost:8000)**

---

## 🛠️ Technologies Used

* **HTML5** – Structure and semantic markup
* **CSS3** – Styling, Flexbox, Grid, responsiveness
* **JavaScript (ES6+)** – DOM manipulation, modules, local storage
* **Google Fonts** – Roboto font

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create a branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ❤️ Author

Developed with ❤️ by **Jishan Shaikh**
