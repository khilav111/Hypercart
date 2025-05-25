🛒 HyperCart - Full-Fledged E-commerce Platform


HyperCart is a full-fledged e-commerce platform designed to provide a seamless and user-friendly online shopping experience. From product discovery to secure payment and order management, HyperCart has everything needed to run a modern online store.

🚀 Tech Stack
Frontend: React.js (Vite)

Backend: Node.js + Express.js

Database: MongoDB

Authentication: Firebase (Firebase Auth + Admin SDK)

Payments: Stripe

🧩 Features
👤 User Authentication and Management
Firebase handles user registration and login (email/password, Google sign-in).

JWT ID tokens are issued on login, and verified via Firebase Admin SDK on the backend.

Backend securely uses uid to perform user-specific operations.

📦 Product & Order Management
Products and orders are stored in MongoDB.

Users can browse products, add them to cart, and place orders.

Admin dashboard allows:

Adding/updating/deleting products

Managing order statuses

Viewing detailed order information

💳 Payment Integration
Stripe integration ensures secure and smooth payment processing.

Users can make payments using credit/debit cards via Stripe Checkout.

🌟 Unique Features
Advanced product filtering & search

Real-time sales and inventory monitoring via admin dashboard

Responsive design optimized for both desktop and mobile

Clear distinction between user and admin roles

📸 Screenshots
🏠 Homepage
![Screenshot 2025-05-22 235625](https://github.com/user-attachments/assets/5ac96079-3240-4eff-9f7c-f8b1bcf552f0)

![Screenshot 2025-05-22 235702](https://github.com/user-attachments/assets/49978e30-6efa-4395-bc82-5c77b8a1c0be)


📊 Admin Dashboard
![Screenshot 2025-05-22 235758](https://github.com/user-attachments/assets/028a936b-236b-4457-a8b3-d98bf5cdb44f)


Product Creation  
![Screenshot 2025-05-22 235819](https://github.com/user-attachments/assets/a654399f-a9a8-4f7a-9f34-7b8ee639c608)

Payment Processing 
![Screenshot 2025-05-22 235906](https://github.com/user-attachments/assets/cdf1a7db-0e7d-4429-8a9c-da95850e347c)

Order Info 
![Screenshot 2025-05-23 000036](https://github.com/user-attachments/assets/3f3c845f-a6ed-46b3-8282-82fa740fe063)






❓ Why This Stack?
React.js: Fast rendering, reusable components, and hooks-based state management.

Node.js + Express.js: Lightweight, scalable backend framework ideal for REST APIs.

MongoDB: Great fit for schema-less data like user profiles and product listings.

Firebase: Simplifies authentication and ID token management.

Stripe: Secure, developer-friendly API with global support for online payments.

🛠️ Project Setup
Prerequisites
Node.js ≥ 14.x

MongoDB Atlas (or local MongoDB)

Firebase project set up (Auth enabled)

Stripe account (API keys)

Installation Steps
bash
Copy
Edit
git clone https://github.com/khilav111/Hypercart
cd Hypercart
# Install backend and frontend dependencies
```cd backend && npm install
cd ../frontend && npm install```

Configuration
Create the following .env files:

🔐 Backend (backend/.env)
env
Copy
Edit
```PORT=5000
MONGODB_URI=your_mongodb_connection_string
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_PRIVATE_KEY=your_private_key
FIREBASE_CLIENT_EMAIL=your_client_email
STRIPE_SECRET_KEY=your_stripe_secret_key
⚙️ Frontend (frontend/.env)```
env
Copy
Edit
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
Running Locally
bash
Copy
Edit
# Start the backend
cd backend
npm run dev

# Start the frontend
cd ../frontend
npm run dev

