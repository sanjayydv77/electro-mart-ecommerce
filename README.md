# 🛒 Electro-Mart E-Commerce Platform

A full-stack e-commerce web application built with Node.js, Express, and MySQL. Features user authentication, product management, shopping cart, and order processing.

## 🌐 Live Demo

**🔗 Visit Live Site:** [https://ecom-electromart.netlify.app/](https://ecom-electromart.netlify.app/)

**Backend API:** [https://electro-mart-ecommerce-1.onrender.com](https://electro-mart-ecommerce-1.onrender.com)

### Deployment Status:
- ✅ Frontend: Deployed on Netlify
- ✅ Backend: Deployed on Render
- ✅ Database: Live Aiven MySQL instance

## ✨ Features

- **User Authentication**: Secure registration and login with bcrypt password hashing
- **Product Management**: Browse and search products with detailed information
- **Shopping Cart**: Add, update, and remove items from cart
- **Order Processing**: Complete checkout and view order history
- **Admin Panel**: Manage products, orders, and view analytics
- **User Profile**: Update personal information and view order history
- **Responsive Design**: Modern UI with particle effects and smooth animations

## 🚀 Tech Stack

**Deployment:**
- Frontend Hosting: Netlify
- Backend Hosting: Render
- Database: Aiven Cloud MySQL

**Backend:**
- Node.js
- Express.js
- MySQL2 with connection pooling
- bcrypt for password encryption
- CORS enabled
- dotenv for environment variables

**Frontend:**
- Vanilla JavaScript
- HTML5 & CSS3
- Modern UI with particle effects
- Fetch API for backend communication

## 📋 Prerequisites

**For Local Development:**
- Node.js (v14 or higher)
- npm or yarn
- MySQL database (or Aiven Cloud account)

**For Production Deployment:**
- GitHub account (for version control)
- Netlify account (for frontend hosting)
- Render account (for backend hosting)
- Aiven account (for managed MySQL database)

## 🌟 Quick Start

### Try the Live App:
Simply visit: **[https://ecom-electromart.netlify.app/](https://ecom-electromart.netlify.app/)**

No installation needed! The app is fully deployed and ready to use.

### Local Development Setup:

1. **Clone the repository**
   ```bash
   git clone https://github.com/sanjayydv77/electro-mart-ecommerce.git
   cd electro-mart-ecommerce
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create .env file**
   
   Copy `.env.example` to `.env` and add your credentials:
   ```env
   DB_HOST=your-database-host.aivencloud.com
   DB_USER=your-username
   DB_PASSWORD=your-password
   DB_NAME=ecom
   DB_PORT=24468
   NODE_ENV=development
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Access locally**
   - Backend: `http://localhost:3001`
   - Frontend: Open `index.html` in your browser

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

**Base URL (Production):** `https://electro-mart-ecommerce-1.onrender.com`

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


## � Deployment

This project is deployed and live!

### Production Stack:
- **Frontend:** Netlify (https://ecom-electromart.netlify.app/)
- **Backend:** Render (https://electro-mart-ecommerce-1.onrender.com)
- **Database:** Aiven Cloud MySQL (managed database service)

### Environment Variables (Render):
Set these in your Render dashboard:
```
DB_HOST=your-aiven-host.aivencloud.com
DB_USER=your-username
DB_PASSWORD=your-password
DB_NAME=ecom
DB_PORT=24468
NODE_ENV=production
```

For detailed deployment instructions, see [DEPLOYMENT_INSTRUCTIONS.md](DEPLOYMENT_INSTRUCTIONS.md)

## �📝 TODO

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

Sanjay Yadav - [@sanjayydv77](https://github.com/sanjayydv77)

**Live Project:** [https://ecom-electromart.netlify.app/](https://ecom-electromart.netlify.app/)

## 🙏 Acknowledgments

- Font: Inter from Google Fonts
- Database: Aiven Cloud MySQL
- Icons and UI inspiration from modern e-commerce platforms

---

⭐ Star this repo if you find it helpful!
