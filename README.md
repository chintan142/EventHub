# 🎉 EventHub

A modern **MERN Stack Event Management & Booking Platform** designed to simplify event organization and ticket booking. EventHub enables users to explore events, reserve seats through a secure verification process, and track their bookings, while administrators can manage events, monitor bookings, and oversee platform activity from a dedicated dashboard.

Built with **MongoDB, Express.js, React, Node.js, Tailwind CSS**, and **Nodemailer**.

---

## ✨ Highlights

* 🔐 Secure user authentication with JWT
* 📧 Email OTP verification for account activation
* 🎟️ OTP-protected event booking
* 👤 User and Admin role management
* 📅 Create and manage free & paid events
* 💺 Automatic seat availability tracking
* 📊 Admin analytics dashboard
* 📨 Booking confirmation emails
* 📱 Fully responsive interface
* ⚡ Fast and modern React frontend

---

# 📌 Core Features

## 👥 Authentication

* User Registration
* Secure Login
* Password encryption using **bcrypt**
* JWT-based authentication
* Email OTP verification for account activation

---

## 🎫 Event Booking

Users can:

* Browse available events
* View complete event details
* Book free or paid events
* Verify booking using Email OTP
* Cancel pending bookings
* Track booking status from their dashboard

---

## 🛠️ Admin Dashboard

Administrators have complete control over the platform.

### Event Management

* Create events
* Edit event details
* Delete events
* Manage event capacity
* Upload event images via URL

### Booking Management

* View booking requests
* Approve or reject bookings
* Update payment status
* Prevent overbooking

### Dashboard Analytics

View important platform statistics such as:

* Total Events
* Pending Requests
* Confirmed Bookings
* Paid Bookings
* Revenue Overview

---

## 📧 Email Notifications

Automatic emails are sent for:

* Account verification
* Booking confirmation
* Booking status updates

Powered by **Nodemailer**.

---

# 🖥️ Tech Stack

### Frontend

* React
* Tailwind CSS
* React Router
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt
* Nodemailer

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/your-username/EventHub.git
cd EventHub
```

---

## 2. Configure Environment Variables

Create a `.env` file inside the **server** folder.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_gmail_app_password
PORT=5000
```

---

## 3. Install Dependencies

From the project root:

```bash
npm install
npm run install:all
```

Or install manually.

### Backend

```bash
cd server
npm install
```

### Frontend

```bash
cd client
npm install
```

---

## 4. Run the Project

From the root directory:

```bash
npm run dev
```

Or run separately.

### Backend

```bash
cd server
npm run dev
```

Runs on:

```text
http://localhost:5000
```

### Frontend

```bash
cd client
npm run dev
```

Runs on:

```text
http://localhost:5173
```

---

# 📂 Project Structure

```text
EventHub
│
├── client
│   ├── src
│   ├── public
│   └── package.json
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   └── package.json
│
├── package.json
└── README.md
```

---

# 🔒 Security Features

* JWT Protected Routes
* Password Hashing with bcrypt
* Email OTP Verification
* Role-Based Authorization
* Booking Validation
* Seat Availability Protection

---

# 💡 Why EventHub?

Managing event registrations manually can quickly become difficult. EventHub provides an organized workflow where users can securely reserve seats while administrators efficiently manage events, bookings, and payments from one centralized platform.

Whether it's a college fest, workshop, seminar, conference, or community meetup, EventHub streamlines the entire booking experience.

---

# 📸 Screenshots

Add screenshots of your application here.

```
Home Page
Admin Dashboard
Event Details
Booking Page
User Dashboard
```

---

# 🚀 Future Enhancements

* Online Payment Gateway Integration
* QR Code Based Tickets
* Event Search & Filters
* User Profile Management
* Event Reviews & Ratings
* Push Notifications
* Multi-language Support

---

# 📄 License

This project is created for learning and portfolio purposes.

Feel free to fork, explore, and build upon it.

---

## ⭐ Show Your Support

If you like this project, don't forget to **star ⭐ the repository** and share your feedback!

Happy Coding! 🚀
