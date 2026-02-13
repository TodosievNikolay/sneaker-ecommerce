🚀 Sneaker E-Commerce Platform

Modern full-stack e-commerce web application for sneaker sales.

Built with React (Vite), FastAPI, and PostgreSQL.
Implements RESTful API, JWT authentication, shopping cart logic, and scalable backend architecture.

🧱 Tech Stack
🖥 Frontend

React (Vite)

JavaScript

Axios

TailwindCSS

🐍 Backend

FastAPI

SQLAlchemy

PostgreSQL

JWT Authentication

🐳 DevOps

Docker

Docker Compose

✨ Features

🔐 JWT Authentication (Register / Login)

👟 Product Catalog

🛒 Shopping Cart

📦 Order Processing

🗄 PostgreSQL Database

📄 Auto-generated Swagger API Docs

🐳 Dockerized Database

🏗 Architecture
Frontend (React)
        ↓
REST API (FastAPI)
        ↓
PostgreSQL


Clean separation of frontend and backend inside a single monorepo.

📁 Project Structure
sneaker-ecommerce/
│
├── frontend/        # React client
├── backend/         # FastAPI server
├── docker-compose.yml
└── README.md

⚙ Installation & Setup
1️⃣ Clone repository
git clone https://github.com/your-username/sneaker-ecommerce.git
cd sneaker-ecommerce

2️⃣ Start PostgreSQL (Docker)
docker-compose up -d

3️⃣ Backend Setup
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload


Backend runs on:

http://localhost:8000


Swagger docs:

http://localhost:8000/docs

4️⃣ Frontend Setup
cd frontend
npm install
npm run dev


Frontend runs on:

http://localhost:5173

🔐 API Overview
Method	Endpoint	Description
POST	/auth/register	Register user
POST	/auth/login	Login user
GET	/products	Get all products
GET	/products/{id}	Get single product
POST	/cart	Add to cart
POST	/orders	Create order
👥 Team Roles

Backend Developer #1 – Core API, Authentication, Database design

Backend Developer #2 – Cart, Orders, Business logic

Frontend Developer – UI + API integration

UI/UX Designer – Layout & user experience

🎯 Project Goal

Build a production-ready full-stack e-commerce system
to demonstrate real-world team collaboration and architecture.

📌 Future Improvements

Stripe Integration

Admin Dashboard

Product Filtering

Pagination

Performance Optimization

📜 License

This project is for educational and portfolio purposes.
