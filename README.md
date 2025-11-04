# Vingo - Food Delivery Application

A full-stack food delivery application built with React, Node.js, and MongoDB that connects customers with local restaurants and delivery partners.

<img width="1760" height="990" alt="Screenshot 2025-11-05 010800" src="https://github.com/user-attachments/assets/e14d2c97-685c-4417-a338-dbd3741a2408" />
<img width="1760" height="990" alt="Screenshot 2025-11-05 005833" src="https://github.com/user-attachments/assets/9047f024-32ff-4f35-967f-263002dc969d" />
<img width="1760" height="990" alt="Screenshot 2025-11-05 010541" src="https://github.com/user-attachments/assets/ffdb5116-4346-4767-9973-3811bfac5f59" />
<img width="1760" height="990" alt="Screenshot 2025-11-05 010643" src="https://github.com/user-attachments/assets/69256780-182b-45c4-b315-d132063c125b" />
<img width="1760" height="990" alt="Screenshot 2025-11-05 010744" src="https://github.com/user-attachments/assets/a3cf6e59-137b-49b5-8b71-69f3e56c2671" />


## Features

- **User Authentication**

  - Sign up/Sign in functionality
  - Forgot password recovery
  - Role-based access (Customer, Shop Owner, Delivery Partner)

- **Customer Features**

  - Browse restaurants by city
  - View menu items and categories
  - Add items to cart
  - Place and track orders
  - View order history
  - Real-time order tracking

- **Shop Owner Features**

  - Create and manage shop profile
  - Add/Edit menu items
  - Manage orders
  - Dashboard with order statistics

- **Delivery Partner Features**
  - Accept delivery assignments
  - Real-time location tracking
  - Order delivery management

## Tech Stack

### Frontend

- React + Vite
- Redux for state management
- Real-time updates with Socket.IO
- Firebase integration
- Location tracking and maps integration

### Backend

- Node.js + Express
- MongoDB for database
- Socket.IO for real-time communication
- JWT authentication
- Cloudinary for image storage
- Email service integration

## Project Structure

### Frontend Structure

```
frontend/
├── src/
│   ├── components/    # Reusable UI components
│   ├── pages/        # Main application pages
│   ├── hooks/        # Custom React hooks
│   ├── redux/        # State management
│   └── assets/       # Images and static assets
```

### Backend Structure

```
backend/
├── controllers/      # Request handlers
├── models/          # Database models
├── routes/          # API routes
├── middlewares/     # Custom middlewares
├── config/          # Configuration files
└── utils/           # Helper functions
```

## Getting Started

1. Clone the repository

```bash
git clone https://github.com/ganesh8068/Vingo.git
cd Vingo
```

2. Install dependencies

```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables

- Create `.env` files in both frontend and backend directories
- Add necessary environment variables

4. Run the application

```bash
# Start backend server
cd backend
npm start

# Start frontend development server
cd frontend
npm run dev
```

## Environment Variables

### Frontend

```
VITE_API_URL=
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
```

### Backend

```
PORT=
MONGODB_URI=
JWT_SECRET=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Ganesh - [@ganesh8068](https://github.com/ganesh8068)

Project Link: [https://github.com/ganesh8068/Vingo](https://github.com/ganesh8068/Vingo)
