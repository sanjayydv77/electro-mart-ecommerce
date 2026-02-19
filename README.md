# 🛒 Electro-Mart E-Commerce Platform

A full-stack e-commerce web application built with Node.js, Express, and MySQL. Features user authentication, product management, shopping cart, and order processing.

## ✨ Features

- **User Authentication**: Secure registration and login with bcrypt password hashing
- **Product Management**: Browse and search products with detailed information
- **Shopping Cart**: Add, update, and remove items from cart
- **Order Processing**: Complete checkout and view order history
- **Admin Panel**: Manage products, orders, and view analytics
- **User Profile**: Update personal information and view order history
- **Responsive Design**: Modern UI with particle effects and smooth animations

## 🚀 Tech Stack

**Backend:**
- Node.js
- Express.js
- MySQL (Aiven Cloud Database)
- bcrypt for password encryption
- CORS enabled

**Frontend:**
- Vanilla JavaScript
- HTML5 & CSS3
- Modern UI with particle effects

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MySQL database (or Aiven Cloud account)

## 📁 Project Structure

```
ecom-project/
├── server.js           # Express server and API routes
├── client.js           # Frontend JavaScript logic
├── index.html          # Login/Register page
├── shop.html           # Product listing page
├── cart.html           # Shopping cart page
├── orders.html         # Order history page
├── profile.html        # User profile page
├── admin.html          # Admin dashboard
├── package.json        # Project dependencies
├── .gitignore          # Git ignore rules
└── README.md           # Project documentation
```

## 🔐 API Endpoints

### Authentication
- `POST /api/register` - Register new user
- `POST /api/login` - User login

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get product by ID
- `POST /api/products` - Add new product (Admin)
- `PUT /api/products/:id` - Update product (Admin)
- `DELETE /api/products/:id` - Delete product (Admin)

### Cart
- `GET /api/cart/:userId` - Get user's cart
- `POST /api/cart` - Add item to cart
- `PUT /api/cart/:id` - Update cart item
- `DELETE /api/cart/:id` - Remove cart item

### Orders
- `POST /api/orders` - Create new order
- `GET /api/orders/:userId` - Get user's orders
- `GET /api/admin/orders` - Get all orders (Admin)

### User
- `GET /api/user/:userId` - Get user profile
- `PUT /api/user/:userId` - Update user profile


## 📝 TODO

- [ ] Add payment gateway integration
- [ ] Implement product reviews and ratings
- [ ] Add email notifications
- [ ] Create product categories and filters
- [ ] Implement search functionality
- [ ] Add wishlist feature
- [ ] Mobile app version

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 👤 Author

Your Name - [Sanjay yadav](https://github.com/Sanjayydv77)

## 🙏 Acknowledgments

- Font: Inter from Google Fonts
- Database: Aiven Cloud MySQL
- Icons and UI inspiration from modern e-commerce platforms

---

⭐ Star this repo if you find it helpful!
