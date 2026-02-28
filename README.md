🛒 ShopEZ : one-stop shop for online purchases
📌 Project Overview : 
ShopEZ is a full‑stack e‑commerce web application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to register, log in, browse products, add items to a cart, and place orders. The system also includes admin functionality for managing users and orders.

🚀 Features  : User Registration & Login (JWT Authentication)
- Secure Password Encryption (bcrypt)
- Product Listing Page
- Add to Cart Functionality
- Persistent Cart Data
- Checkout & Order Placement
- Order Storage in MongoDB
- Admin Dashboard (View Users & Orders)
- Full Frontend–Backend Integration

🛠️ Technologies Used : Frontend --> React (Vite) , HTML5 , CSS , JavaScript
Backend --> Node.js , Express.js , MongoDB , Mongoose , JWT (JSON Web Token)

📂 Project Structure :
ShopEZ/
│
├── client/        # React Frontend (Vite)
├── server/        # Express Backend + MongoDB
└── control-panel/ # System health check dashboard

⚙️ Installation & Setup :
1️⃣ cd ShopEZ
2️⃣ Setup Backend
- cd server
- npm install
- npm run dev

Backend runs on : http://localhost:5000 3️⃣ Setup Frontend

Open a new terminal :
- cd client
- npm install
- npm run dev

Frontend runs on: http://localhost:5173

🧪 How to Test the Application :
- Register a new user
- Login with credentials
- Browse products
- Add products to cart
- Proceed to checkout
- Confirm order
- Verify order stored in MongoDB

🔐 Authentication Flow : User registers → password encrypted using bcrypt
- User logs in → JWT token generated
- Token stored in localStorage
- Protected routes use middleware verification

🗄️ Database Collections : Users , Products , Cart ,Orders

📊 System Architecture : Frontend (React)
                                ⬇
                        Backend (Express API)
                                ⬇
                         MongoDB Database


🎯 Project Objective : The objective of ShopEZ is to demonstrate full‑stack web development using the MERN stack, including authentication, REST APIs, database integration, and frontend–backend communication.
