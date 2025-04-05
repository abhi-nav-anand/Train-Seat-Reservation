# Train Seat Reservation System

A MERN stack application to reserve train seats with smart seat allocation logic.

## 🔧 Tech Stack

- **Frontend**: Vite + React + Tailwind CSS
- **Backend**: Node.js + Express.js
- **Database**: MongoDB
- **Authentication**: JWT-based user login/signup
- **Hosting**:
  - Deploy: [Live Link](https://train-seat-res.netlify.app/) 🔗
  - GitHub: [Repo Link](https://github.com/abhinavanand3154/train-seat-reservation) 🔗

---

## 📌 Features

-  **User Authentication**
  - Signup/Login functionality
  - JWT tokens for secure API calls

- 💺 **Seat Reservation**
  - 80 seats in total (7 per row, last row has 3)
  - One user can book **up to 7 seats at once**
  - Prioritizes booking in the **same row**
  - If unavailable, books **adjacent** nearby seats
  - Prevents **double booking**
  - Booking history per user

- 🧹 **Admin Features**
  - Reset All Bookings

---

## 🖼️ UI Preview

| Home Page             | Seat Booking Page         |
|-----------------------|---------------------------|
| ![Home](https://drive.google.com/file/d/1ORThHo0JSML0Uum9gQLspw2LDYFT9l0v/view?usp=sharing) | ![Booking](https://drive.google.com/file/d/1Hpi51-rQLSO8eA0e0iGzV8zYsKpta_wZ/view?usp=sharing) |

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/abhinavanand3154/train-seat-reservation.git
cd train-seat-reservation
