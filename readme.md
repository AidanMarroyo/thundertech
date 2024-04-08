# ThunderTech - Your Go-To E-commerce Platform 🛒⚡

Welcome to ThunderTech, the comprehensive e-commerce platform built with the MERN stack. ThunderTech offers a wide range of features designed to create a seamless shopping experience for both customers and administrators. Dive into our full-featured shopping cart, explore products through reviews, ratings, and a top products carousel, and manage your orders with ease. Whether you're a shopper looking for your next purchase or an admin managing the platform, ThunderTech has something for everyone.

## Features 🌟

- Full-featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin order details page
- Option to mark orders as delivered
- Checkout process (including shipping and payment method selection)
- PayPal / credit card integration
- Database seeder for products & users

## Usage 🚀

1. **Create a MongoDB database** and obtain your MongoDB URI from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
2. **Create a PayPal account** and obtain your Client ID from [PayPal Developer](https://developer.paypal.com/).

## Env Variables 🔒

Rename the `.env.example` file to `.env` and update it with your details:

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
PAGINATION_LIMIT = 8
```

Change the JWT_SECRET and PAGINATION_LIMIT to what you want

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@email.com (Admin)
123456

john@email.com (Customer)
123456

jane@email.com (Customer)
123456
```

---
