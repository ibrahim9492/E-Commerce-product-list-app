# 🛍️ React UI Replication Project

A fully responsive, component-driven React application built to replicate the exact design and functionality from a provided Figma file. This project demonstrates pixel-perfect UI implementation, modular architecture, and dynamic interactivity using React and Tailwind CSS.

---

## 🚀 Live Demo

🌐 Hosted Link: [Click here to view the app](https://e-commerce-product-list-app.vercel.app/)  
📦 GitHub Repo: [https://github.com/ibrahim9492/E-Commerce-Product-List-app](https://github.com/ibrahim9492/E-Commerce-Product-List-app)

---

## 📁 Folder Structure

├── public/
│ └── index.html
├── src/
│ ├── assets/ # All static images and icons
│ ├── components/ # Reusable UI components (Navbar, Cards, Filters, etc.)
│ ├── pages/ # Route-based page components (Login, Dashboard, Profile, etc.)
│ ├── layouts/ # Layout components (DashboardLayout, etc.)
│ ├── context/ # Global context providers (if used)
│ ├── data/ # JSON mock data used for dynamic rendering
│ ├── App.jsx # Main application component with routes
│ ├── main.jsx # ReactDOM entry point
│ └── index.css # Tailwind CSS & global styles

markdown
Copy
Edit

---

## 🧩 Features

### ✅ UI Replication

- Pixel-perfect UI implementation based on Figma
- Typography, spacing, icons, buttons, and forms matched as per design

### ⚛️ Component-Based Architecture

- All UI elements are broken into modular, reusable functional components
- Examples: `Navbar`, `ProductCard`, `CategoryFilter`, `LoginForm`, `MobileMenu`

### 🔀 Routing with React Router

- Route-based rendering using `react-router-dom`
- Pages include:
  - `/login`
  - `/dashboard`
  - `/profile`
  - `/products`
  - `* (404 page)`

### 🔄 State Management

- `useState` and `useEffect` used for local state and side-effects
- Optional: `Context API` used for global state (e.g., Auth, Theme Toggle)

### 🧠 Dynamic Behavior

- Mock data rendered using `.json` files from `/data`
- Filtering, toggling, search, and form handling implemented

### 📱 Responsive Design

- Fully responsive using Tailwind’s utility classes
- Mobile menu toggle, grid-to-flex switches, adaptive typography

---

## 🛠️ Technologies Used

- **React.js** (v18)
- **Tailwind CSS** (v3)
- **React Router DOM**
- **Mock JSON Data / Fake APIs**
- **Optional**: `json-server` or `Context API`

---

## 💡 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/ibrahim9492/E-Commerce-Product-List-app.git

# Navigate into the project directory
cd E-Commerce-Product-List-app

# Install dependencies
npm install

# Start development server
npm run dev

📌 Git Best Practices Followed

Descriptive commit messages

Modular file organization

Branching for features

Clear project structure with comments

👨‍💻 Author

Ibrahim Shaik

📧 ibrahimkhalandar02@gmail.com

🔗 LinkedIn

📃 License

This project is licensed under the MIT License. Feel free to use and modify it for personal or commercial purposes.
