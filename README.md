#  Airline Booking System

A full-stack Airline Booking System built using modern web technologies. This application allows users to search for flights, book tickets, select seats, and manage their bookings, while providing administrative tools for managing flight data.

---

##  Features

###  User Features

* User Registration and Login
* Flight Search and Filtering
* Flight Booking System
* Seat Selection (interactive)
* Add-ons (baggage, meals, priority boarding)
* View Booking History
* Secure Payment Integration

###  Admin Features

* Create, Read, Update, Delete (CRUD) Flights
* Manage flight availability and schedules

---

##  Advanced Features (Planned / Optional)

* Smart flight recommendations
* Booking countdown timer
* E-ticket generation
* Dark mode UI
* Real-time seat availability simulation

---

##  Tech Stack

### Frontend

* Vue.js (Composition API)
* Vue Router
* Pinia (State Management)
* Axios
* Notyf (Notifications)

### Backend (Planned / Optional)

* Node.js
* Express.js
* MongoDB (Mongoose)

---

##  Project Structure

```bash
Airline-Booking-System/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── router/
│   └── store/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
```

---

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-repo/airline-booking-system.git
cd airline-booking-system
```

### 2. Install dependencies

Frontend:

```bash
cd frontend
npm install
npm run dev
```

Backend (if applicable):

```bash
cd backend
npm install
npm run dev
```

---

##  Authentication

* Uses token-based authentication (JWT planned)
* Role-based access (User / Admin)

---

##  ERD Overview

Core Entities:

* Users
* Flights
* Bookings
* Booking Items (Tickets)
* Seats
* Add-ons
* Payments

---

##  Future Improvements

* Payment gateway integration (Stripe / PayMongo)
* Email confirmation system
* Flight status updates (real-time)
* Mobile responsiveness enhancements

---

##  Contributors

* **Paulo Espinosa**
* **Jackielyn Clavaton**

---

##  License

This project is for educational and portfolio purposes.

---

##  Notes

This project demonstrates:

* Frontend state management
* Component-based architecture
* RESTful API integration
* Real-world booking system logic

---
