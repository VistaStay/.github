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


### **State Management (Redux Toolkit)**
Used for **global state handling** across the app.  
- **User Authentication State**  
- **Hotel List & Filters State**  
- **Booking State**  
- **Payment Process State**  


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



## 📬 Contact
📧 **Email:** [your-email@vistastay.com](mailto:your-email@vistastay.com)  


## 🎉 Pages

### 🔹 Homepage
<img width="950" alt="Image" src="https://github.com/user-attachments/assets/67aaaefd-d0ff-49dd-8fa3-eb3799085d22" />

### 🔹 Trending hotels(AI search filtering section)
<img width="952" alt="Image" src="https://github.com/user-attachments/assets/4551f9d6-373a-4084-b8a1-44ab5b28c3f2" />

### 🔹 AI search
<img width="959" alt="Image" src="https://github.com/user-attachments/assets/aa46aef8-4b61-43bb-b422-a15ef578ebf0" />

### 🔹 Booking hotels with dates
<img width="959" alt="Image" src="https://github.com/user-attachments/assets/e2f65ed2-bbf0-4d9d-bb73-57f669214466" />

### 🔹 Payment page
<img width="954" alt="Image" src="https://github.com/user-attachments/assets/d0ea5991-4e2e-45ef-a926-4a991baf767e" />

### 🔹 Create hotel
<img width="950" alt="Image" src="https://github.com/user-attachments/assets/0518a613-d84b-4f82-98b2-ac51a01d82b8" />

### 🔹 filtering hotel section
<img width="958" alt="Image" src="https://github.com/user-attachments/assets/711de0b6-72a2-4a57-829d-2e0edf20211b" />

### 🔹 filtered hotel
<img width="951" alt="Image" src="https://github.com/user-attachments/assets/5f78fc64-f5ba-4e8c-9d8f-3a63b15038aa" />

### 🔹 Booking page
<img width="955" alt="Image" src="https://github.com/user-attachments/assets/7fdfd58e-bf90-41e9-83fa-7ed7bb78dc99" />

### 🔹 Filters
<img width="960" alt="Image" src="https://github.com/user-attachments/assets/7efca2e4-c52a-441c-bfb8-ff7d73bdee26" />

### 🔹 Payment page
<img width="954" alt="Image" src="https://github.com/user-attachments/assets/d0ea5991-4e2e-45ef-a926-4a991baf767e" />
