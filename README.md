# 🎬 Screen-Sizzle -- Movie Booking System

## 📌 Introduction
The **Movie Booking System** is a web-based platform designed to provide movie enthusiasts with an easy and seamless experience in discovering, exploring, and booking tickets for their favorite movies. With a vast collection of movies, including classics and the latest releases, users can search, filter, and get detailed information such as reviews, ratings, and cast details. The platform aims to enhance the overall movie-watching experience by integrating features such as online booking, food selection, and multiple payment options.

## 🎯 Project Goal
The goal of this project is to offer a user-friendly system where movie lovers can conveniently book tickets, select their preferred cinema, choose movie schedules, and make hassle-free payments. The system caters to individual moviegoers as well as group bookings for schools and colleges, making it an all-in-one movie ticketing solution.

---

## 🚀 Features
### 🏷️ User Features
- Browse the list of available movies.
- View movie details, including cast, reviews, and ratings.
- Search and filter movies based on preferences.
- View available cinemas and their schedules.
- Register and log in to manage personal accounts.
- Book tickets for selected movies.
- Select the desired cinema, date, and time for a show.
- Choose from different ticket types (Gold, Premium, etc.).
- Select food items while booking tickets.
- View and manage booking history.
- Make secure payments via Stripe.
- Receive confirmation emails for bookings.

### 🛠️ Admin Features
- Add or remove movies from the system.
- Manage cinemas and their details.
- Update and manage movie schedules.
- Create and manage promotions and deals.
- View and manage user bookings.
- Ensure system security and prevent unauthorized access.

---

## 📜 Functional Requirements
### 🎥 Movie Management
- The system shall display a list of available movies.
- The admin shall be able to add, update, or remove movies.

### 🎭 Cinema & Schedule Management
- The system shall display all cinemas.
- The admin shall be able to add or remove cinemas.
- The system shall show movie schedules (screen timings).
- The admin shall be able to add and update movie schedules.

### 📋 Booking & Ticketing
- The system shall allow users to book tickets for available movies.
- The system shall provide options for Gold and Premium ticket selections.
- Users shall be able to select the number of seats while booking.
- Users shall be able to choose food items during ticket booking.
- The system shall support group bookings for schools and colleges.

### 🔑 User Authentication
- The system shall support user registration and login.
- Users shall be able to update their personal information.

### 💳 Payment Processing
- The system shall support secure transactions via Stripe.
- Users shall receive email confirmations upon successful bookings.

### ⭐ Reviews & Promotions
- The system shall display user reviews for movies.
- The system shall showcase promotions and discount deals.

---

## 🛠️ Technologies Used
### **Frontend**
- **React.js** – For building a dynamic and responsive UI.
- **React Bootstrap** – For styling and user interface components.

### **Backend**
- **Node.js** – For handling server-side logic.
- **Express.js** – For building RESTful APIs.

### **Database**
- **MongoDB** – For storing movie, user, and booking data.

### **Payment Gateway**
- **Stripe (Test Mode)** – For secure online payments.

### **Email Service**
- **Nodemailer** – For sending booking confirmation emails.

---

## 🛠️ Installation & Setup

### Prerequisites
Ensure you have the following installed on your system:
- Node.js (v14 or later)
- MongoDB (local or cloud-based)
- A Stripe test account for payment processing

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-repo/movie-booking-system.git
cd movie-booking-system
```

### Step 2: Install Dependencies
#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd frontend
npm install
```

### Step 3: Configure Environment Variables
Create a `.env` file in the backend directory and add the following details:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
STRIPE_SECRET_KEY=your_stripe_secret_key
EMAIL_SERVICE=your_email_service
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

### Step 4: Start the Application
#### Run the Backend Server
```bash
cd backend
npm start
```

#### Run the Frontend Server
```bash
cd frontend
npm start
```

---

## 🎯 Future Enhancements
- Implement AI-based movie recommendations.
- Introduce social sharing features for users to share bookings.
- Enhance the admin dashboard with analytics and reports.
- Enable QR code-based ticket scanning for hassle-free check-ins.
- Add multi-language support for a global audience.

---

## 🤝 Contributing
We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your fork.
5. Submit a pull request.

---

## 📞 Contact
For any queries or support, reach out to us at:
📧 Email: hananaslam90@gmail.com


Happy Movie Watching! 🎥🍿

