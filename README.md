# 📱 Phone Catalog

An interactive and responsive online store built with **React**, showcasing a catalog of gadgets including phones, tablets, and accessories. Users can browse products, add them to favorites or the shopping cart, and view detailed product pages — all in a clean, intuitive interface.

[🔗 DEMO LINK](https://sophiasph.github.io/phone-catalog/)
**Design (Figma)**: (https://www.figma.com/design/BUusqCIMAWALqfBahnyIiH/Phone-catalog-(V2)-Original-Dark)

---

## 📌 Overview

This project simulates the product catalog of the **Nice Gadgets** online store. The website allows users to:

- Browse phones, tablets, and accessories
- Sort and filter products
- View detailed information about each product
- Add products to favorites or shopping cart
- Navigate via sticky header and breadcrumb paths
- Interact with a dynamic slider, pagination, modals, and smooth animations

It was developed to practice advanced React concepts, TypeScript, Redux, modular architecture, and clean UI practices.

---

## 🎮 Features

### General
- Sticky header with navigation, cart, and favorites counters
- Responsive design for all screen sizes
- Smooth hover effects and image scaling
- "Back to top" button with smooth scrolling
- NotFoundPage for unknown routes

### Home Page
- Hero image slider (auto-changes every 5s, with navigation dots)
- Hot Prices slider (sorted by biggest discount)
- Brand New section (sorted by newest items)
- Shop by category links

### Product Categories
- Sort by: Newest, Alphabetically, Cheapest
- Pagination and items per page selection
- Error states and loaders
- Empty catalog messages if no products available

### Product Details Page
- View multiple images, tech specs, and description
- Choose color and capacity variants
- Add to cart and favorites
- "You may also like" recommendations
- Breadcrumb navigation and "Back" button
- Handle product not found gracefully

### 🛒 Cart Page
- Add/remove products with quantity controls
- Total price and total items summary
- Modal checkout confirmation
- State saved to `localStorage`

### ❤️ Favorites Page
- Add/remove products from favorites
- Real-time update of favorites count
- Favorites also saved to `localStorage`

---

## 🛠 Technologies Used

- **React**
- **React Router**
- **Redux**
- **TypeScript**
- **SCSS / BEM**
- **Vite**
- **HTML5**
- **Responsive Layout**

---

## 🛠 How to run the project:

Follow these instructions to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/sophiasph/phone-catalog.git
cd phone-catalog
```

### 2. Install Dependencies
Ensure you have Node.js (version 18.x or higher) installed. Then run:
```bash
npm install
```

### 3. Run the Project Locally
To start the development server, run:
```bash
npm run dev
```
