<div align="center">

<!-- BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=200&section=header&text=ForeverBuy&fontSize=70&fontColor=e8c170&fontAlignY=38&desc=Your%20Premium%20Fashion%20Destination&descAlignY=58&descSize=18&descColor=a8b2d8" width="100%"/>

<br/>

<!-- LIVE BADGES -->
[![Live Frontend](https://img.shields.io/badge/🛍️%20Live%20Store-ForeverBuy-e8c170?style=for-the-badge&labelColor=0f3460&color=e8c170)](https://forever-frontend-peach-tau.vercel.app/)
[![Admin Panel](https://img.shields.io/badge/⚙️%20Admin%20Panel-Dashboard-a8b2d8?style=for-the-badge&labelColor=16213e&color=a8b2d8)](https://forever-admin-taupe-six.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-shouryaaa8-white?style=for-the-badge&logo=github&labelColor=1a1a2e)](https://github.com/shouryaaa8/ForeverBuy)

<br/>

<!-- TECH STACK BADGES -->
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## ✨ What is ForeverBuy?

**ForeverBuy** is a full-stack e-commerce platform built with the **MERN stack** — offering a seamless, modern shopping experience for fashion enthusiasts. From browsing collections to secure checkout, it covers the complete e-commerce lifecycle with a clean UI and a powerful admin panel.

> 🛍️ Shop. 🧾 Order. 📦 Track. — All in one place.

---

## 🖥️ Project Structure

```
ForeverBuy/
├── 📁 frontend/       → React + Vite — Customer-facing storefront
├── 📁 backend/        → Node.js + Express — REST API & business logic
└── 📁 admin/          → React — Admin dashboard for store management
```

---

## 🚀 Features

### 🛒 Customer Storefront
- 🏠 **Home Page** — Hero banner, featured collections & latest arrivals
- 👗 **Collections Page** — Filter by category, subcategory & price
- 🔍 **Product Detail Page** — Size selector, image gallery & descriptions
- 🛍️ **Shopping Cart** — Add, remove & update item quantities
- 💳 **Checkout** — Secure order placement with Stripe & Razorpay
- 📦 **Order Tracking** — View order history and current status
- 🔐 **Authentication** — Register & login with JWT-based sessions

### ⚙️ Admin Dashboard
- 📋 **Product Management** — Add, edit & delete products with images
- 📦 **Order Management** — View all orders and update delivery status
- 📤 **Image Uploads** — Cloudinary + Multer for fast media handling

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React, Vite, Tailwind CSS, React Router |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB + Mongoose |
| **Auth** | JSON Web Tokens (JWT) |
| **Payments** | Stripe, Razorpay |
| **Media** | Cloudinary, Multer |
| **Deployment** | Vercel (Frontend + Admin), Render/Railway (Backend) |

---

## ⚡ Getting Started

### Prerequisites
- Node.js `v18+`
- MongoDB Atlas account (or local MongoDB)
- Cloudinary account
- Stripe / Razorpay API keys

### 1. Clone the Repository

```bash
git clone https://github.com/shouryaaa8/ForeverBuy.git
cd ForeverBuy
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside `/backend`:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret
STRIPE_SECRET_KEY=your_stripe_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
ADMIN_EMAIL=admin@foreveryou.com
ADMIN_PASSWORD=your_admin_password
```

```bash
npm run server
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

### 4. Setup Admin Panel

```bash
cd ../admin
npm install
npm run dev
```

> 🌐 Frontend runs on `http://localhost:5173`
> ⚙️ Admin runs on `http://localhost:5174`
> 🔧 Backend runs on `http://localhost:4000`

---

## 🌍 Live Deployment

| App | URL |
|---|---|
| 🛍️ Customer Store | [forever-frontend-peach-tau.vercel.app](https://forever-frontend-peach-tau.vercel.app/) |
| ⚙️ Admin Dashboard | [forever-admin-taupe-six.vercel.app](https://forever-admin-taupe-six.vercel.app/) |

---

## 📁 API Overview

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/api/user/register` | Register new user |
| `POST` | `/api/user/login` | Login user |
| `GET` | `/api/product/list` | Get all products |
| `POST` | `/api/product/add` | Add new product (Admin) |
| `DELETE` | `/api/product/remove` | Remove a product (Admin) |
| `POST` | `/api/cart/add` | Add item to cart |
| `POST` | `/api/order/place` | Place a new order |
| `GET` | `/api/order/userorders` | Get user's orders |
| `POST` | `/api/order/stripe` | Stripe payment |
| `POST` | `/api/order/razorpay` | Razorpay payment |

---

## 🤝 Contributing

Contributions are welcome! Here's how:

```bash
# 1. Fork the repo
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature"

# 4. Push and open a Pull Request
git push origin feature/your-feature-name
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>

**Made with ❤️ by [shouryaaa8](https://github.com/shouryaaa8)**

*If you found this useful, consider giving it a ⭐ on GitHub!*

</div>
