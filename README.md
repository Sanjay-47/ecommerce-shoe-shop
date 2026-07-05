# Stride - Premium Running & Athletic Shoes E-Commerce Shop

A full-stack ecommerce platform for selling premium running and athletic shoes. Built with modern web technologies inspired by the Balmoral Running website design.

## Features

- 🛒 Complete shopping cart functionality
- 🔐 User authentication & authorization
- 💳 Checkout & payment processing
- 📦 Product catalog with filtering & search
- 👤 User account management
- 📱 Fully responsive design (mobile-first)
- ⚡ Fast performance with Next.js
- 🎨 Clean, modern UI with Tailwind CSS

## Tech Stack

### Frontend
- **Next.js 14** - React framework with app router
- **React 18** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **Zustand** - State management
- **Axios** - HTTP client
- **React Icons** - Icon library

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **JWT** - Authentication
- **Bcrypt** - Password hashing

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Sanjay-47/ecommerce-shoe-shop.git
cd ecommerce-shoe-shop
```

2. **Install all dependencies**
```bash
npm install
cd client && npm install && cd ..
cd server && npm install && cd ..
```

3. **Set up environment variables**
```bash
cp .env.example .env.local
```

### Running the Application

**Development Mode**
```bash
npm run dev
```

**Or run separately:**
```bash
# Terminal 1
npm run client

# Terminal 2
npm run server
```

### Access the Application
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000/api

## Project Structure

```
ecommerce-shoe-shop/
├── client/                 # Next.js frontend
│   ├── app/               # Pages
│   ├── components/        # Reusable components
│   ├── store/            # Zustand stores
│   └── package.json
│
├── server/                 # Express backend
│   ├── routes/            # API routes
│   ├── config/            # Configuration
│   ├── server.js          # Entry point
│   └── package.json
│
└── package.json           # Root package.json
```

## API Endpoints

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get single product
- `POST /api/products` - Create product
- `PUT /api/products/:id` - Update product
- `DELETE /api/products/:id` - Delete product

### Orders
- `POST /api/orders` - Create order
- `GET /api/orders/:id` - Get order
- `GET /api/orders/user/:userId` - Get user orders

### Auth
- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Login user

## Features in Development

- [ ] Payment gateway integration
- [ ] Admin dashboard
- [ ] Product reviews
- [ ] Wishlist functionality
- [ ] Advanced search
- [ ] Email notifications

## License

MIT License
