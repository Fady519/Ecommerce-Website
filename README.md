# 🛒 Trendify - Advanced E-Commerce Web Application

A high-performance, fully responsive E-Commerce Single Page Application (SPA) built using **React.js** and **Vite**. The application delivers a seamless shopping experience across 4 distinct product categories, featuring advanced cart management, personalized product favorites, and a secure multi-step checkout flow.

## 🚀 Live Demo & Repository
- **Live Application:** [Deploy Link](https://fady519.github.io/Ecommerce-Website/login)
- **GitHub Repository:** [Source Code](https://github.com/Fady519/Ecommerce-Website)

---

## ⚡ Performance & Engineering Highlights

This project wasn't just built for functionality; it was engineered for speed, responsiveness, and scale:

*   **Optimized Performance:** Applied **route-based code splitting** and **lazy loading** (`React.lazy` and `Suspense`), cutting the initial JavaScript bundle into smaller async chunks to achieve faster first-paint rendering and better Lighthouse scores.
*   **Fluid Motion & UX:** Integrated **Framer Motion** page transitions and micro-interactions across 6 key UI states, significantly enhancing perceived responsiveness without introducing layout shifts (CLS).
*   **Robust Form Validation:** Enforced schema-based validation on 4 multi-step checkout forms using **React Hook Form**, dynamically blocking submission on 10+ error conditions with instant, helpful inline user feedback.
*   **State Management:** Scalable and predictable global state architecture powered by the native **Context API** to handle cart mechanics, favorites lists, and user session state globally.

---

## ✨ Key Features

- **🔐 Dynamic Authentication:** Clean multi-state user authentication pages (Login / Register).
- **🛍️ Complete Cart Mechanics:** Live addition, subtraction, real-time total calculations, and item removal.
- **❤️ Wishlist / Favorites System:** Toggle items to easily save them for later purchases.
- **📦 4 Main Categories:** Organized catalog layout with clean routing for structured product browsing.
- **💳 Multi-Step Checkout:** A guided, validation-guarded user flow simulating a production-grade checkout system.
- **📱 Fully Responsive Design:** Tailored layouts ensuring pixel-perfect viewing experiences from mobile devices to desktop monitors.

---

## 🛠️ Tech Stack & Architecture

*   **Frontend Library:** React.js (Hooks & Functional Components)
*   **Build Tool:** Vite (For blazing-fast compilation and HMR)
*   **State Management:** Context API
*   **Form Handling:** React Hook Form
*   **Animation Engine:** Framer Motion
*   **Routing:** React Router DOM
*   **Styling:** Modern Responsive CSS (Flexbox / Grid Layouts)

---

## ⚙️ Local Development Setup

To run this project locally, follow these quick steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Fady519/Ecommerce-Website.git](https://github.com/Fady519/Ecommerce-Website.git)
