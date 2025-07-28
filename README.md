# 🛒 E-Commerce Store

![App Screenshot](/frontend/public/screenshot-for-readme.png)

## 🌍 Live Demo

🔗 **Live Site**: [https://e-commerce-store-aypt.onrender.com](https://e-commerce-store-aypt.onrender.com)  
⚠️ _Please note: This is hosted on a free render.com plan, so the first load may take up to 30 seconds while the server spins up._

## 📦 Overview

A fully-featured modern **e-commerce web application** built from scratch with:

- **Frontend**: React.js + Redux Toolkit + Tailwind CSS
- **Backend**: Node.js + Express + MongoDB
- **Extras**: Stripe, Redis, JWT Auth, Cloudinary

Users can browse products, add to cart, apply coupon codes, and securely checkout using Stripe. Admins can manage products, categories, view sales analytics, and more.

## ✨ Features

### 🔹 Frontend (React + Redux Toolkit + Tailwind CSS)

- ⚛️ Modern React SPA
- 🎨 Responsive UI with Tailwind
- 🧠 Redux Toolkit for state management
- 🛒 Full shopping cart functionality
- 🔑 Login & Register with JWT
- 💳 Stripe checkout
- 🏷️ Apply coupon codes
- 📱 Mobile-friendly

### 🔹 Backend (Node.js + Express + MongoDB)

- 🛠️ REST API
- 🔐 JWT Auth with Refresh Tokens
- 👤 Role-based access (user/admin)
- 🗃️ MongoDB for users, products, orders
- ☁️ Cloudinary for image uploads
- 📊 Admin dashboard with sales analytics
- ⚡ Redis caching
- 📦 Product & category CRUD

## 🧪 Environment Setup

Create a `.env` file in the `backend/` folder:

```env
PORT=5000
MONGO_URI=your_mongo_uri
UPSTASH_REDIS_URL=your_redis_url
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

## 🚀 Getting Started Locally

### 1. Clone the Repository

```bash
git clone https://github.com/adams-id/e-commerce-store.git
cd e-commerce-store
```

### 2. Install Backend Dependencies

```bash
npm install
```

### 3. Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 4. Build the Frontend

```bash
npm run build
```

### 5. Start the Server

```bash
cd ..
npm run start
```

App runs on: [http://localhost:5000](http://localhost:5000)  
Frontend (if served separately): [http://localhost:5173](http://localhost:5173)

## 🧠 Future Improvements

- 📝 Product reviews & ratings
- 📬 Email confirmation and password reset
- 🧾 Order tracking
- ❤️ Wishlist functionality
- 📱 PWA support

## 📜 License

Licensed under the **MIT License**.
