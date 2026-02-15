# 🛍️ Vibe Market  
### Full-Stack Fashion & Lifestyle E-Commerce Platform

**Vibe Market** is a scalable, production-ready full-stack e-commerce application designed for modern fashion and lifestyle retail. The platform delivers a seamless shopping experience with secure authentication, real-time cart management, integrated payments, and an advanced admin dashboard.

It supports a wide range of products including apparel, footwear, accessories, and lifestyle essentials.

---

## 🚀 Key Highlights

- Secure JWT-based authentication with Redis-backed session handling  
- Category-based product browsing with responsive UI  
- Dynamic cart management with real-time updates  
- Discount coupon engine integrated at checkout  
- Stripe-powered secure payment processing  
- Admin dashboard with product control and analytics  
- Fully responsive across devices  

---

## 🧩 System Architecture

Vibe Market follows a clean separation of concerns with independent frontend and backend services.

### 🔹 Frontend

- React 18  
- Zustand (State Management)  
- TailwindCSS (Utility-first styling)  
- Framer Motion (Animations)  
- Recharts (Sales analytics visualization)  
- Lucide React (Icons)  

### 🔹 Backend

- Node.js  
- Express.js  
- MongoDB with Mongoose  
- Redis (Caching & session optimization)  
- JWT (Authentication & authorization)  
- Cloudinary (Media storage)  
- Stripe (Payment processing)  

---

## 📂 Project Structure

```
vibe-market/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── lib/
│   ├── seeds/
│   └── server.js
│
└── frontend/
    ├── public/
    └── src/
        ├── components/
        ├── pages/
        ├── stores/
        └── lib/
```

---

## ⚙️ Setup & Installation

### Prerequisites

- Node.js (v16+)
- MongoDB
- Redis
- Stripe account
- Cloudinary account

---

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Sarthakmittal8/vibe-market.git
cd vibe-market
```

---

### 2️⃣ Install Dependencies

```bash
npm install
cd frontend
npm install
cd ..
```

---

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```
PORT=5000
NODE_ENV=development

MONGO_URI=your_mongodb_connection_string

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

UPSTASH_REDIS_URL=your_redis_url

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
```

---

### 4️⃣ (Optional) Seed Database

```bash
node backend/seeds/seedDatabase.js
```

---

### 5️⃣ Start Development Server

```bash
npm run dev
```

---

## 🛒 Platform Capabilities

### 👤 Customer

- Browse products by category  
- Add, update, and remove cart items  
- Apply discount coupons  
- Complete secure Stripe checkout  
- View order history  

### 🛠️ Admin

- Access dashboard via `/secret-dashboard`  
- Create, update, and manage products   
- Toggle featured products  
- Monitor sales analytics  

---

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.  
Feel free to fork the repository and submit a pull request.
