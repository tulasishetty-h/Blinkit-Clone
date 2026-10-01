# 🛒 Blinkit Web Clone

A responsive frontend clone of **Blinkit** (formerly Grofers) — India's leading quick-commerce grocery delivery platform. Built using semantic **HTML5** and modern **CSS3**, this project recreates the clean, fast, and intuitive user interface of the Blinkit web application.

---

## 📸 Overview & Features

- **🧭 Sticky Navigation Bar**:
  - Official Blinkit branding & logo
  - Dynamic delivery ETA badge (*Delivery in 8 minutes*) & location picker
  - Interactive search bar with search suggestions placeholder
  - Quick-access **Login** and **My Cart** buttons with icon support
- **🎉 Promotional Hero Banner**: Eye-catching top promotional banner displaying seasonal offers and featured categories.
- **🏷️ Quick Promo Cards**: Highlighted order categories (Pharmacy, Pet Care, Baby Products).
- **🗂️ Category Grid**: Multi-row visual category browser covering everyday essentials (Dairy & Breakfast, Cold Drinks, Snacks, Paan Corner, Instant Food, and more).
- **🛍️ Product Showcase Sections**:
  - **Dairy, Bread & Eggs**
  - **Rolling Paper & Tobacco / Paan Corner**
  - Product cards equipped with:
    - High-resolution product images
    - Discount badge ribbons (e.g., *20% OFF*)
    - ETA indicators (◷ *8 MINS*)
    - Product titles, quantities/units (e.g., *500g*, *6 pcs*)
    - MRP strike-through and discounted selling price (₹)
    - Interactive **ADD** buttons with hover transitions
- **📱 App Download Banner**: Promotional card linking to iOS App Store & Google Play Store.
- **📑 Comprehensive Footer**:
  - Multi-column navigation links (Useful Links, Company, Franchise, Seller, Partner)
  - Full product category directory
  - App download badges and social media icons (Facebook, Twitter/X, Instagram, LinkedIn)
  - Legal disclaimer and copyright information
- **📱 Fully Responsive Design**: Mobile-first media queries supporting desktops, tablets, and mobile screens.

---

## 📁 Project Structure

```text
blinkit/
├── index.html         # Main semantic HTML structure
├── style.css          # CSS styles, layout variables, and responsive media queries
├── images/            # Product assets, category icons, logos, and UI graphics
└── README.md          # Project documentation
```

---

## 🛠️ Tech Stack

- **HTML5**: Semantic markup, accessible element hierarchies, and layout structures.
- **CSS3**:
  - CSS Custom Properties (Variables) for color schemes (`--green: #0c831f`, `--text: #1c1c1c`, etc.)
  - Flexbox & CSS Grid layouts
  - Responsive media queries (`@media`) for multi-device support
  - Custom scrollbars, badge overlays, and button micro-interactions

---

## 🚀 Getting Started

No build tools or external package dependencies are required to run this project locally.

### 1. Clone or Download the Repository

```bash
git clone https://github.com/your-username/blinkit-clone.git
cd blinkit
```

### 2. Open the Project

You can simply open the `index.html` file in any modern web browser:

- **Directly in Browser**: Double-click `index.html` or drag and drop it into your browser.
- **Using VS Code Live Server**: Right-click `index.html` and select **"Open with Live Server"**.
- **Using Python's Built-in HTTP Server**:
  ```bash
  # Python 3
  python3 -m http.server 8000
  ```
  Then navigate to `http://localhost:8000` in your browser.

---

## 🎨 Color Palette Reference

| Color Name | Hex Code | Preview | Usage |
| :--- | :--- | :--- | :--- |
| **Blinkit Green** | `#0c831f` | ![#0c831f](https://via.placeholder.com/15/0c831f/000000?text=+) | Primary brand color, CTA buttons, discount badges |
| **Dark Charcoal** | `#1c1c1c` | ![#1c1c1c](https://via.placeholder.com/15/1c1c1c/000000?text=+) | Primary headings and text |
| **Muted Grey** | `#666666` | ![#666666](https://via.placeholder.com/15/666666/000000?text=+) | Subtitles, descriptions, units |
| **Soft Background** | `#f8f8f8` | ![#f8f8f8](https://via.placeholder.com/15/f8f8f8/000000?text=+) | Card hover states, backgrounds |
| **Border Line** | `#eeeeee` | ![#eeeeee](https://via.placeholder.com/15/eeeeee/000000?text=+) | Dividers, card borders, navbar border |

---

## 💡 Future Enhancements

- [ ] JavaScript-powered functional cart (Increment/Decrement quantity, Cart drawer modal, Total Price calculation)
- [ ] Live product search & filtering functionality
- [ ] Category filtering and category detail pages
- [ ] User authentication modal (OTP / Phone login simulation)
- [ ] Dark mode toggle support

---

## ⚖️ Disclaimer

This project is created strictly for **educational and portfolio demonstration purposes**. All brand names, logos, product images, and trademarks belong to their respective owners (Blink Commerce Private Limited / Blinkit).
