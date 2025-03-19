# Forever - E-commerce Application

![Forever](https://scintillating-sawine-6137b5.netlify.app/collection)

## Description
Forever is a comprehensive online marketplace offering over 10,000 products for buying and selling. The application provides a seamless user experience with features like filtering, searching, cart management, authentication, and more.

## Live Demo
🔗 [Forever E-commerce App](https://scintillating-sawine-6137b5.netlify.app/collection)

## Features
- 🔍 **Product Filtering & Searching**
- 🛒 **Add to Cart & Checkout**
- ✏️ **CRUD Operations** (Admin Panel for product management)
- 🔑 **JWT Authentication** for secure access
- 🖼 **Multer for Image Uploading**
- 🎨 **Modern UI** built with Vite & ReactJS

## Tech Stack
### Frontend:
- ReactJS (Initialized with Vite)
- Tailwind CSS for styling

### Backend:
- Node.js with Express.js
- MongoDB with Mongoose
- Multer for file storage

### Authentication & Security:
- JWT Token-based authentication
- Cookie & LocalStorage for user session management

## Installation & Setup
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/your-username/forever-ecommerce.git
cd forever-ecommerce
```

### 2️⃣ Install dependencies:
#### Frontend:
```bash
cd frontend
npm install
npm run dev
```
#### Backend:
```bash
cd backend
npm install
npm start
```

### 3️⃣ Environment Variables:
Create a `.env` file in the backend directory and add:
```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

## Deployment
- Frontend hosted on **Netlify**
- Backend hosted on **Render/Vercel** (or any cloud platform of choice)

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.
