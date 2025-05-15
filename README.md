# 🛍️ PokeStore - Flutter E-commerce App

**👤 Student Name:**   Stefan D. Amper
**🆔 Student ID:** 2023-219881

---

## 🌟 Overview

Welcome to **PokeStore**, a fun and immersive mobile e-commerce UI built with Flutter. This app is themed around Pokémon merchandise, specifically **Poké Balls** and **Potions**. It offers a smooth and engaging shopping experience with beautifully styled components, mock product data, and a streamlined checkout process.

Designed with a focus on **UI/UX** principles, PokeStore prioritizes usability, visual appeal, and simplicity over backend complexity.

---

## 📲 Features Implemented

### 🔹 Splash Screen
- A simple, branded loading screen to welcome users (optional but included).

### 🔹 Home / Product Listing Screen
- Grid layout displaying Pokémon items.
- Product cards with images, names, prices, and categories.
- Search bar to filter by name.
- Dropdown menu for filtering by **Poké Balls** or **Potions**.
- Navigation to detailed product view.

### 🔹 Product Detail Screen
- Shows full product info: image, description, name, price.
- Quantity selector.
- Add to Cart button.

### 🔹 Cart Screen
- View items added to cart.
- Modify item quantity.
- Remove items from cart.
- Shows subtotal and total prices.
- Proceed to Checkout button.

### 🔹 Checkout Screen
- Collects customer info: name, address, city, zip.
- Payment method selection UI.
- Order summary with items and prices.
- Place Order button leading to confirmation screen.

### 🔹 Order Confirmation Screen
- Simple message confirming successful order.

---

## 🎨 Design Highlights

### 🧭 Theme & Niche
- Based on the Pokémon universe, appealing to fans and gamers.
- Focuses on a specific product range to simulate a real niche store.

### 🎨 Colors & Fonts
- Primary color: **Red** (inspired by Poké Balls).
- Clean, white backgrounds with bold accents.
- Font: **Roboto** for a modern and readable experience.

### 🖼️ Visuals
- All product images are Pokémon-themed.
- Custom layout for product cards with spacing and style.

### 🧩 UI/UX Enhancements
- Search functionality.
- Filtering by category.
- Real-time updates to cart.
- Animated transitions between screens.
- Reusable and modular widgets.

---

## 🧠 Development Challenges

### 🔧 Image Asset Issues
- **Problem:** Only one image loaded properly.
- **Fix:** Verified image names and extensions, converted `.jfif` files to `.png`, and correctly declared them in `pubspec.yaml`.

### 🔍 Search & Filter Logic
- **Problem:** Making search and category filtering work together.
- **Fix:** Used `TextEditingController`, stateful filtering, and applied both conditions in the product list query.

---

## 📸 Screenshots (Add yours!)

- `screenshots/home.png`  
- `screenshots/product_detail.png`  
- `screenshots/cart.png`  
- `screenshots/checkout.png`  
- `screenshots/confirmation.png`

---

## 🛠️ Tech Stack

- **Flutter 3.0+**
- **Dart**
- **Material UI**

---

## 🚀 Getting Started

1. Clone the repo or download the source code.
2. Make sure images are placed in `assets/images/`.
3. Run the following commands:

```bash
flutter pub get
flutter run
