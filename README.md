# 🛒 E-Commerce Store

A full-stack E-Commerce web application built using **Node.js, Express.js, MongoDB, Mongoose, EJS, and Bootstrap**. Users can browse products, register/login, manage their shopping cart, and place orders.

---

## 🚀 Features

### 👤 User Authentication
- User Registration
- User Login & Logout
- Session-based Authentication
- Password Hashing using bcrypt

### 🛍️ Product Management
- View all products
- View product details
- Add new products
- Edit products
- Delete products

### 🛒 Shopping Cart
- Add products to cart
- Increase/Decrease quantity
- Remove products from cart
- View cart total

### 📦 Order Management
- Checkout
- Order History
- Automatic cart clearing after checkout
- Product stock updates after order placement

### 💾 Database
- MongoDB Atlas
- Mongoose ODM

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- EJS

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- express-session
- bcrypt
- connect-flash

---

## 📁 Project Structure

```
ecommerce/
│
├── config/
│   └── db.js
│
├── controllers/
│   ├── authController.js
│   ├── cartController.js
│   ├── orderController.js
│   └── productController.js
│
├── middleware/
│   └── isLoggedIn.js
│
├── models/
│   ├── User.js
│   ├── Product.js
│   ├── Cart.js
│   └── Order.js
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── routes/
│   ├── auth.js
│   ├── product.js
│   ├── cart.js
│   └── order.js
│
├── views/
│   ├── auth/
│   ├── cart/
│   ├── orders/
│   ├── products/
│   └── layouts/
│
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ecommerce-store.git
```

### 2. Navigate to the project

```bash
cd ecommerce-store
```

### 3. Install dependencies

```bash
npm install
```

### 4. Create a `.env` file

```env
PORT=3000

MONGO_URI=your_mongodb_connection_string

SESSION_SECRET=your_secret_key
```

### 5. Start the application

```bash
npm start
```

or

```bash
nodemon app.js
```

Open your browser and visit:

```
http://localhost:3000
```

---

## 📚 Dependencies

- express
- mongoose
- ejs
- ejs-mate
- express-session
- bcrypt
- connect-flash
- method-override
- dotenv

---

## 🔮 Future Improvements

- Product Search
- Category Filters
- Product Reviews & Ratings
- Wishlist
- Razorpay/Stripe Payment Gateway
- Cloudinary Image Upload
- Admin Dashboard
- User Profile
- Responsive Navbar with Cart Count

---

## 📸 Screenshots

Add screenshots of:
- Home Page
- Product Listing
- Product Details
- Shopping Cart
- Checkout
- Order History

---

## 👨‍💻 Author

**Abhishek Singh**

GitHub: https://www.linkedin.com/in/abhishek-singh-4628b7262
LinkedIn: 
https://www.linkedin.com/in/abhishek-singh-4628b7262
---

## 📄 License

This project is developed for learning and portfolio purposes.
