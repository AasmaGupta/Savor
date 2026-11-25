# DineCloud – Cloud-Based Restaurant Management System

DineCloud is a web-based restaurant management and online food ordering platform that simplifies restaurant operations through a unified system.

## Features
- Browse food menu and manage shopping cart.
- Place orders and track order status.
- Admin authentication using JWT.
- Menu and order management.
- Inventory and recipe-based stock management.
- Analytics dashboard for sales and order insights.
- Browser push notifications using Firebase Cloud Messaging.

## Tech Stack
- **Frontend:** React.js, Vite, Material UI, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas, Mongoose
- **Authentication:** JWT
- **Cloud Services:** Cloudinary, Firebase Cloud Messaging
- **Tools:** Git, GitHub, Postman

## Architecture

```text
Customer / Admin
       |
 React + Vite
       |
   REST APIs
       |
 Node.js + Express
       |
  +----+---------+
  |    |         |
MongoDB Cloudinary Firebase
 Atlas   Images    FCM
```

## Installation

```bash
git clone https://github.com/Bhavika-web/DineCloud.git
cd DineCloud

cd frontend
npm install
npm run dev
```

Configure the required environment variables for the backend, MongoDB Atlas, Firebase and Cloudinary before running the backend.

## Deployment
- **Frontend:** Vercel
- **Backend:** Render
- **Database:** MongoDB Atlas
- **Images:** Cloudinary
- **Notifications:** Firebase Cloud Messaging

**Live Links:**
- Frontend: https://dine-cloud.vercel.app
- Backend: https://dinecloud.onrender.com

## Future Scope
- Online payment integration.
- Customer accounts and order history.
- Advanced inventory management.
- Multi-restaurant support.
- AI-based demand forecasting and recommendations.

## Project Objective

To integrate cloud services and modern web technologies into a unified restaurant management platform, improving ordering, inventory tracking and administrative operations.
