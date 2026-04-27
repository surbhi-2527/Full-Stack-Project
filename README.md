# Service Marketplace Platform

A full-stack Service Marketplace web application built using **React.js** for connecting users with service providers through an easy booking and communication platform.

## Features

### Authentication
- User Registration
- User Login
- Profile Management
- Protected Routes
- Role-based access

### User Module
- Browse available services
- Filter services
- View service details
- Book services
- Manage bookings
- Chat with providers
- Wallet management
- Profile dashboard

### Provider Module
- Provider Dashboard
- Create services
- Edit services
- Manage service listings
- View bookings
- Chat with customers
- Wallet / Earnings tracking
- Provider profile management

### Admin Module
- Manage Users
- Manage Services
- Monitor Bookings
- Handle Disputes
- Payment Logs
- Admin Dashboard

### Additional Features
- Real-time chat UI
- Transaction history
- Wallet balance tracking
- Responsive design
- Reusable component architecture

---

## Tech Stack

### Frontend
- React.js
- React Router DOM
- Context API
- Material UI
- Emotion Styling
- Lucide React Icons

### Backend
- API Integration Ready (Axios Service Layer)

### State Management
- AuthContext
- BookingContext
- ChatContext
- WalletContext

---

## Project Structure

```bash
src/
│── assets/
│── components/
│   ├── admin/
│   ├── auth/
│   ├── booking/
│   ├── chat/
│   ├── common/
│   ├── layout/
│   ├── service/
│   └── wallet/
│
│── context/
│── hooks/
│── pages/
│   ├── admin/
│   ├── auth/
│   ├── provider/
│   └── user/
│
│── routes/
│── services/
│── utils/
│── App.js
│── index.js
```

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move into project folder:

```bash
cd fullstack-project
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm start
```

Runs on:

```bash
http://localhost:3000
```

---

## Available Scripts

### Run project
```bash
npm start
```

### Production build
```bash
npm run build
```

### Run tests
```bash
npm test
```

---

## Core Components

### Authentication
- LoginForm
- RegisterForm
- ProfileForm

### Booking
- BookingCard
- BookingForm
- BookingSummary
- PaymentModeSelector
- TimeSlotPicker

### Chat
- ChatList
- ChatWindow
- MessageBubble
- MessageInput

### Service
- ServiceCard
- ServiceFilters
- ServiceForm
- ServiceList

### Wallet
- WalletBalanceCard
- TransactionTable
- PendingCashTransfers

---

## Future Improvements
- Backend integration
- Payment gateway
- Notifications
- Live chat sockets
- Reviews & Ratings
- Search optimization
- Mobile app support

---

## Author
Developed as a Full Stack Project using React.js.
