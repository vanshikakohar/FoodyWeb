# 🍽️ Foody Web

**Foody Web: Online Food Delivery App** — a Full-stack web application built with the **MERN stack** (MongoDB, Express, React, Node.js).  
It allows users to browse a dynamic menu, place orders, and securely complete transactions through an integrated payment system.

---

## 🚀 Features

- **User Authentication:** Secure login and signup using bcryptjs and JWT tokens for session management.  
- **Dynamic Menu:** Fetches and displays food items from MongoDB with a real-time search feature.  
- **Checkout & Payment:** Smooth order placement and payment via **Razorpay integration**.  
- **Responsive Design:** Built with **Bootstrap** and **Bootstrap-Dark** for an adaptive user interface.

---

## 🧠 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | React.js, Bootstrap 5, Bootstrap-Dark-5 |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Atlas) |
| **Authentication** | bcryptjs, JWT |
| **Payment Gateway** | Razorpay |

---

## 📁 Repository Structure

FoodyWeb/
│
├── backend/
│ ├── Routes/
│ ├── models/
│ ├── db.js
│ └── index.js
│
├── src/
│ ├── components/
│ ├── screens/
│ ├── App.js
│ └── index.js
│
└── package.json

---

## 💻 Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/vanshikakohar/FoodyWeb.git
cd FoodyWeb
2️⃣ Install dependencies
npm install

3️⃣ Run the frontend
npm start

4️⃣ Run the backend
cd backend
npm install
npm start

⚙️ Environment Variables

Create a .env file in the backend folder and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
PORT=5000

👩‍💻 Author

Vanshika Kohar
🔗 GitHub

⭐ Don’t forget to star this repository if you found it useful!


---

### 🪄 To Apply the Fix

1. Open your `README.md` in VS Code or any editor.  
2. Delete everything in it.  
3. Paste the formatted Markdown above.  
4. Save → then push it:
   ```bash
   git add README.md
   git commit -m "Formatted README.md properly"
   git push origin main
