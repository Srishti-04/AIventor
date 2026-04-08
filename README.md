# 🎟️ AIventor – Event Booking Platform (MERN + AI)

🚀 **Live Repo:** https://github.com/Srishti-04/AIventor  

A full-stack **Event Booking Platform** built using the **MERN stack** with secure authentication, dynamic seat allocation, and AI-powered event generation using **Gemini AI**.

---

## 🚀 Features

- 🔐 Secure Authentication
  - JWT-based login/signup
  - OTP-based email verification

- 📅 Event Management
  - Create, update, delete events (Admin)
  - View and explore events (Users)

- 🎫 Booking System
  - Dynamic seat allocation
  - Real-time booking workflow
  - Booking history tracking

- 📊 Admin Dashboard
  - Full CRUD operations
  - Analytics & insights (bookings, users, events)

- 🤖 AI Integration
  - Gemini AI for intelligent event generation

- 📧 Notifications
  - Automated email notifications for bookings & verification

- 🎨 Responsive UI
  - Built with Tailwind CSS
  - Mobile-first design
  - Improved user engagement (~30%)

---

## 🛠️ Tech Stack

**Frontend**
- React.js
- Tailwind CSS

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB

**Authentication**
- JWT (JSON Web Tokens)
- OTP Verification (Email-based)

**AI Integration**
- Gemini AI API

---

## 📂 Project Structure

/client        → React frontend  
/server        → Node.js backend  
  /controllers → Business logic  
  /routes      → API routes  
  /models      → MongoDB schemas  
  /middlewares → Auth & validation  
  /utils       → Helper functions (OTP, email, etc.)  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Srishti-04/AIventor.git
cd AIventor
```

### 2️⃣ Install dependencies
```bash
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in `/server`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
GEMINI_API_KEY=your_api_key
```

### 4️⃣ Run the application

```bash
# Start backend
cd server
npm run dev

# Start frontend
cd client
npm start
```

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | User registration |
| POST | /api/auth/login | User login |
| POST | /api/events | Create event |
| GET | /api/events | Get all events |
| POST | /api/bookings | Book event |
| GET | /api/admin/stats | Admin analytics |

---

## 🧠 AI Feature (Gemini)

- Generate event ideas automatically  
- Improve event descriptions  
- Assist admin in content creation  

---

## 📈 Impact

- 🚀 Improved user engagement by ~30%  
- ⚡ Smooth and reliable booking lifecycle  
- 🔒 Secure authentication and data handling  

---

## 🧪 Future Improvements

- Payment Gateway Integration (Stripe/Razorpay)  
- Real-time seat updates using WebSockets  
- Recommendation system for users  
- Mobile app version  

---

## 👩‍💻 Author

**Srishti Jaiswal**  
GitHub: https://github.com/Srishti-04  

---

## ⭐ Contribute

Feel free to fork this repo, raise issues, or submit PRs!
