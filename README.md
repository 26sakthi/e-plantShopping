# Paradise Nursery Shopping Application

An elegant, dynamic e-commerce shopping cart web application for **Paradise Nursery**, an online plant nursery where green meets serenity. Built using **React**, **Redux Toolkit**, and **Vite**.

---

## 🌿 About Paradise Nursery

At **Paradise Nursery**, we are passionate about bringing nature closer to your home and workspace. Our mission is to provide a wide selection of high-quality houseplants that enhance the aesthetic appeal of your surroundings and foster a healthier, more sustainable lifestyle.

---

## ✨ Features

- **Interactive Landing Page**:
  - Welcoming hero section with background greenhouse imagery and tagline.
  - Company overview describing Paradise Nursery's mission and commitment to quality.
  - Smooth "Get Started" call-to-action button transitioning directly into the catalog.

- **Categorized Plant Catalog**:
  - Over 30 unique houseplants organized into 5 distinct categories:
    - *Air Purifying Plants* (Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera)
    - *Aromatic Fragrant Plants* (Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth)
    - *Insect Repellent Plants* (Oregano, Marigold, Geraniums, Basil, Lavender, Catnip)
    - *Medicinal Plants* (Aloe Vera, Echinacea, Peppermint, Lemon Balm, Chamomile, Calendula)
    - *Low Maintenance Plants* (ZZ Plant, Pothos, Snake Plant, Cast Iron Plant, Succulents, Aglaonema)
  - Every plant card displays a high-resolution thumbnail, name, description, and price.

- **Dynamic Shopping Cart Management (Redux Toolkit)**:
  - **Add to Cart**: Instantly adds items to the Redux cart state.
  - **Dynamic Cart Counter**: Real-time item count badge directly on the cart icon in the navigation bar.
  - **Button State**: "Add to Cart" button automatically changes to "Added to Cart" and disables once added.
  - **Quantity Adjustments**: Increment (`+`) and decrement (`-`) quantity buttons with real-time recalculations. If quantity reaches 0, the item is removed.
  - **Item Removal**: Dedicated "Delete" button to quickly remove plants from the cart.
  - **Item & Order Totals**: Dynamically displays the subtotal for each item and the total cost for the entire cart.

- **Seamless Navigation**:
  - Persistent navigation bar across both the catalog and cart views.
  - Quick links to return to "Home" (landing page), "Plants" (catalog), or view the "Cart".
  - "Continue Shopping" button on the cart page to easily return to browsing.
  - "Checkout" button with instant user feedback.

---

## 🛠️ Technologies Used

- **React 18**
- **Redux Toolkit** (Global state management for shopping cart)
- **Vite** (Next-generation front-end tooling)
- **JavaScript (ES6+)**
- **CSS3** (Responsive design, flexbox, grid, glassmorphism effects)

---

## 📁 Project Structure

```
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.css
│   ├── AboutUs.jsx       # Company details & mission
│   ├── App.css           # Landing page & global styles
│   ├── App.jsx           # Main landing page & view manager
│   ├── CartItem.css      # Shopping cart styling
│   ├── CartItem.jsx      # Shopping cart page & calculations
│   ├── CartSlice.jsx     # Redux slice for cart actions
│   ├── ProductList.css   # Product grid & navbar styling
│   ├── ProductList.jsx   # Catalog view & navigation bar
│   ├── main.jsx          # App entry point with Redux Provider
│   └── store.js          # Redux store configuration
├── index.html
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16.0 or higher recommended)
- npm or yarn

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/26sakthi/e-plantShopping.git
   ```

2. Navigate to the project directory:
   ```bash
   cd e-plantShopping
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`.

---

## 📦 Building for Production

To create an optimized production build:

```bash
npm run build
```

---

## 📄 License

This project is licensed under the MIT License.