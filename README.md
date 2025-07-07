# 🍽️ FoodFlow - Real-Time Food Ordering Application

FoodFlow is a full-stack web application that connects users with local restaurants for a seamless food ordering experience. Built using the **MERN stack** and **Firebase**, it offers real-time order tracking, secure payment integration, and responsive interfaces for users and administrators.

---

## 🚀 Features

* ✅ User Registration & Authentication
* 🍔 Browse Menus & Place Orders
* 📟 Real-Time Order Tracking (Firebase)
* 💳 Secure Payment Integration
* 🧑‍🍳 Admin Dashboard for Restaurant Management
* 📱 Mobile-First Responsive UI
* 📊 Order Analytics & Reports

---

## 💪 Tech Stack

**Frontend:**

* React.js
* Tailwind CSS

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB (Mongoose)

**Real-Time Updates:**

* Firebase (Realtime Database)

**Other Integrations:**

* Razorpay / Stripe (for Payments)
* JWT (Authentication)

---

## 📂 Project Structure

```bash
cloudproj/
├── backend/             # Express backend for APIs and DB integration
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/            # React-based user interface
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
├── admin/               # Admin panel for restaurant staff
│   ├── public/
│   ├── src/
│   │   └── ...
├── firebase/            # Firebase configs for real-time updates
│   └── firebase.js
├── package.json         # Root project config
└── README.md
```

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ShaileshKumar005/cloudproj.git
cd cloudproj
```

### 2. Setup Environment Variables

Create `.env` files in `backend/` and `frontend/` with the following:

**backend/.env**

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

**frontend/.env**

```env
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_DB_URL=your_firebase_db_url
```

### 3. Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install

# Admin Panel
cd ../admin
npm install
```

### 4. Run the Application

```bash
# Backend
cd backend
npm run dev

# Frontend
cd ../frontend
npm start

# Admin
cd ../admin
npm start
```

---


## 📊 Future Improvements

* Push notifications for order updates
* Integration with delivery partner APIs
* OTP login and address suggestions
* Multi-language support

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 🙇‍♂️ Author

**Shailesh Kumar T S**
[GitHub](https://github.com/ShaileshKumar005) • [LinkedIn](https://linkedin.com/in/shaileshkumarts)
