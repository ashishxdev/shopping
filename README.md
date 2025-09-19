# 🛒 E-commerce Store

A responsive, modular e-commerce web app built with React. Users can browse, search, view product details in a modal, and manage a shopping cart with quantity control.

## 🚀 Features
-   **🔍 Live Search:** Search for products by title.
-   **🏠 Homepage Sections:**
    -   Promo banners
    -   Trending products by category
    -   Recommended section
    -   Collection grid
-   **🧾 Product Modal:** Quick view and add to cart.
-   **🛒 Shopping Cart:**
    -   Quantity +/- controls
    -   Auto-calculated subtotal, tax, delivery, discount, and total
    -   Remove single or all items
-   **📱 Fully Responsive** layout using CSS Modules.

## 🧩 Tech Stack
-   **Frontend:** React, React Router DOM
-   **Styling:** CSS Modules
-   **State Management:** React Hooks (`useState`, `useEffect`)
-   **Routing:** `react-router-dom`
-   **Data:** Fetched from a dummy product API via `productService.js`

## 🗂️ Project Structure
```
src/
│
├── api/                # API fetch logic
│   └── productService.js
├── components/         # Reusable components
│   ├── NavBar.jsx
│   ├── BrandRow.jsx
│   └── ProductModal.jsx
├── pages/              # Route components
│   ├── HomePage.jsx
│   ├── CartPage.jsx
│   └── ShoppingSection.jsx
├── styles/             # CSS Modules
│   └── *.module.css
├── utils/
│   └── getProduct.js   # Product filtering utility
├── App.jsx             # Main app logic and routing
└── main.jsx            # ReactDOM render
```
## 📦 Setup & Installation
1.  **Clone the repo:**
    ```bash
    git clone https://github.com/ashishxdev/shopping.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd shopping
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Run the development server:**
    ```bash
    npm run dev
    ```
5.  **Build for production:**
    ```bash
    npm run build
    ```

## 🔧 Customization
-   Update product filters in `getProduct.js` to adjust logic.
-   Modify styling in `/styles` using CSS Modules.
-   Integrate a backend or cart storage solution as needed.

---
Made with ❤️ using React and CSS Modules.
