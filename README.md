AIWebTech
AIWebTech is a full-stack website template marketplace and AI website platform. Users can browse responsive website demos, create an account, buy website templates, complete payment, and manage purchased websites from a dashboard.

Features
Responsive professional homepage
Multiple website template demos for business sectors
User signup and login
Google login setup
Zoho login demo flow
Mobile OTP demo flow
User dashboard for purchased websites
Admin dashboard for orders and requests
Razorpay-ready payment flow with local demo payment
MySQL database schema for users, orders, requests and websites
AIWebTech AI assistant for template and plan suggestions
WhatsApp and email contact buttons
Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js
Database: MySQL
Integrations: Google OAuth, Razorpay, Zoho login demo, mobile OTP demo
Folder Structure
AIWebTech/
  frontend/   website pages, styles, scripts and template demos
  backend/    Node.js API, MySQL schema and payment/auth routes
Run Backend
cd backend
npm install
npm start
Backend runs on:

http://localhost:5000
Run Frontend
Open frontend/index.html in a browser or use VS Code Live Server.

Environment Setup
Create backend/.env from backend/.env.example and set your real values:

MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=your_mysql_password
MYSQL_DATABASE=aiwebtech
GOOGLE_CLIENT_ID=your_google_client_id
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
Never upload real .env secrets to GitHub.

Project Status
This project is ready for local demo and can be prepared for deployment after adding production API keys, domain, hosting and real payment/SMS credentials.
