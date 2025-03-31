# 🏨 VistaStay - Hotel Booking Platform
Welcome to **VistaStay**! 🌍✨ Your one-stop destination for **seamless hotel booking with AI-powered search, secure payments, and advanced filters.** 🏡💳  
🌐 **Live Demo:** [VistaStay Web App](https://hotelapp-vistastay-frontend-sharada.netlify.app/)  

## 📌 About VistaStay
VistaStay is a **MERN stack** hotel booking platform designed for **smooth and secure** reservations. It offers **AI-enhanced search, flexible filtering options, date-based booking, and Stripe-powered payments.**  

### 🔥 Key Features
✅ **AI-Powered Search** - Smart search powered by **OpenAI**  
✅ **Advanced Filters** - Filter hotels by **location, price (ascending/descending), amenities**  
✅ **Hotel Details** - View hotel cards with detailed descriptions and images  
✅ **Date-Based Booking** - Select check-in & check-out dates, auto-calculating total nights  
✅ **Secure Payment Gateway** - Powered by **Stripe** for safe online transactions  
✅ **User Authentication & Authorization** - Powered by **Clerk**  
✅ **State Management** - **Redux Toolkit** for smooth global state handling  
✅ **Account Page** - View and manage personal booking history and account details  

## 🚀 Tech Stack
### 🏗️ Frontend
- **React.js** - UI development  
- **Redux Toolkit** - State management  
- **Clerk Authentication** - Secure login system  
- **Tailwind CSS** - Modern UI styling  
### 🖥️ Backend
- **Node.js & Express.js** - Backend API  
- **MongoDB Atlas** - Cloud database  
- **JWT & Clerk** - Authentication & authorization  
- **Stripe API** - Secure online payments  
### 🔗 Integrations
- **OpenAI API** - AI-powered search  
- **Stripe Payment Gateway** - Secure checkout process  

## 🏗️ Installation
### 🔹 Clone the Repository
```sh
git clone https://github.com/your-username/VistaStay.git
cd VistaStay
```
### 🔹 Backend Setup
```sh
cd Backend
npm install
npm start
```
### 🔹 Frontend Setup
```sh
cd Frontend
npm install
npm run dev
```

## 🔐 Authentication & State Management
### **User Authentication** (Powered by **Clerk**)
- **Secure user authentication** via **Clerk API**  
- **JWT-based authorization** for protected routes  
- **User roles** - Admin, Hotel Owner, Customer  
#### **Login API**
```sh
POST /api/auth/login
```
- **Request Body**  
```json
{
  "email": "user@example.com",
  "password": "password123"
}
```
- **Response**  
```json
{
  "token": "jwt_token_here",
  "user": { "id": "user_id", "role": "customer" }
}
```
#### **Register API**
```sh
POST /api/auth/register
```
- **Request Body**  
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "securepassword"
}
```

### **State Management (Redux Toolkit)**
Used for **global state handling** across the app.  
- **User Authentication State**  
- **Hotel List & Filters State**  
- **Booking State**  
- **Payment Process State**  
#### **Redux Store Setup**
```js
import { configureStore } from '@reduxjs/toolkit';
import authReducer from './features/authSlice';
import hotelReducer from './features/hotelSlice';
export const store = configureStore({
  reducer: {
    auth: authReducer,
    hotel: hotelReducer,
  },
});
```

## 💳 Stripe Payment Integration
### **Checkout Process**
- **User selects a hotel**  
- **Chooses check-in & check-out dates**  
- **Stripe handles secure payment processing**  
- **User receives a confirmation email**  
#### **Payment API Endpoint**
```sh
POST /api/payment
```
- **Request Body**  
```json
{
  "userId": "user123",
  "amount": 200,
  "currency": "USD"
}
```

## 📜 API Endpoints
### 🔹 Hotels
- `GET /api/hotels` - Get all hotels  
- `GET /api/hotels/:id` - Get a single hotel  
- `POST /api/hotels` - Add a new hotel  
- `PUT /api/hotels/:id` - Update hotel details  
- `DELETE /api/hotels/:id` - Remove a hotel  
### 🔹 Booking
- `POST /api/bookings` - Create a new booking  
- `GET /api/bookings/:userId` - Get all bookings for a user  
### 🔹 Authentication
- `POST /api/auth/register` - Register a new user  
- `POST /api/auth/login` - Login user  
- `GET /api/auth/me` - Get user details  
### 🔹 Payments
- `POST /api/payment` - Process payment via **Stripe**  

## 🛠️ Contributing
We welcome contributions! Please follow these steps:  
1. **Fork the repository**  
2. **Create a new branch** (`feature-name`)  
3. **Commit your changes**  
4. **Push the branch**  
5. **Open a pull request**  
For details, check our [Contribution Guidelines](https://github.com/your-org/VistaStay/blob/main/CONTRIBUTING.md).  

## 📬 Contact
📧 **Email:** [your-email@vistastay.com](mailto:your-email@vistastay.com)  
💬 **Discord:** [Join Our Community](https://discord.gg/your-invite)  
🐦 **Twitter:** [Follow us](https://twitter.com/VistaStay)  

## 🎉 Acknowledgments
A huge thanks to our **team, contributors, and users** for making VistaStay a success! 🚀🎊  
