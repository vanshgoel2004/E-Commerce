# 🛒 Full Stack E-Commerce Application

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

A high-performance, full-stack e-commerce solution featuring a modern UI, secure payments, and a robust administrative backend. Built using the **MERN stack** (MongoDB, Express, React, Node.js).

---

## 🚀 Key Features

- 🔐 **Secure Auth:** JWT-based user authentication (Login/Register).
- 🛍️ **Shopping Experience:** Product filtering, search functionality, and real-time cart updates.
- 💳 **Payment Integration:** Secure checkout flow powered by **PayPal**.
- ☁️ **Media Management:** Seamless image uploads via **Cloudinary**.
- ⭐ **Social Proof:** Product rating and review system.
- 🧑‍💼 **Admin Power:** Full dashboard to manage inventory, update order status, and moderate users.

---

## 🧩 Tech Stack

| Frontend      | Backend    | Cloud & DevOps   |
| :------------ | :--------- | :--------------- |
| React (Vite)  | Node.js    | MongoDB Atlas    |
| Redux Toolkit | Express.js | Cloudinary (CDN) |
| Tailwind CSS  | Mongoose   | PayPal SDK       |

---

## 📁 Project Structure

```text
project/
├── client/           # React frontend (Vite)
│   ├── src/          # Components, Pages, Redux Slices
│   └── public/       # Static assets
├── server/           # Node/Express backend
│   ├── controllers/  # Logic for routes
│   ├── models/       # Mongoose schemas
│   ├── routes/       # API endpoints
│   └── middleware/   # Auth & Error handling
├── .gitignore
└── README.md
```


## ⚙️ Environment Variables

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PAYPAL_CLIENT_ID=your_client_id


## 🛠️ Installation & Setup

 1. Clone & Install

 Clone the repo
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name

 Install Server dependencies
cd server
npm install

 Install Client dependencies
cd ../client
npm install

 2. Run Development Servers
You will need to run two terminals or use a package like concurrently.

Terminal 1 (Backend):

$Bash
cd server
npm run dev

Terminal 2 (Frontend):

$Bash
cd client
npm run dev

