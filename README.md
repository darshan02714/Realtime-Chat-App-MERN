## Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack – MongoDB, Express, React, and Node.js – 
with additional tools and libraries like Socket.IO, Cloudinary, React Router DOM, React Hot Toast, JWT, and bcryptjs
for seamless communication and user management.

---------------------------------------------------------------------------------------------------------------------

 ## 🚀 Features

 * 🔒 Secure authentication using JWT and bcryptjs
 * 📡 Real-time messaging powered by Socket.IO
 * 🖼️ Image upload support using Cloudinary
 * 📍 User presence and typing indicators
 * 📱 Responsive and modern UI with React
 * 🔥 Toast notifications using react-hot-toast
 * 🔄 Client-side routing with react-router-dom

---------------------------------------------------------------------------------------------------------------------

🛠️ Tech Stack

 ## Frontend:

 * React
 * React Router DOM
 * React Hot Toast
 * Axios
 * Socket.IO Client

 ## Backend:

* Node.js
* Express.js
* MongoDB (with Mongoose)
* Socket.IO
* Cloudinary
* JSON Web Token (JWT)
* bcryptjs

---------------------------------------------------------------------------------------------------------------------

## 📁 Project Structure

```
/chat-app
  ├── /backend
  │    ├── controllers/
  │    ├── middleware/
  │    ├── models/
  │    ├── routes/
  │    └── server.js
  ├── /frontend
  │    ├── src/
  │    │    ├── components/
  │    │    ├── pages/
  │    │    ├── context/
  │    │    └── Index.js
  └── README.md
```

---------------------------------------------------------------------------------------------------------------------

## ⚙️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app
   ```

2. **Backend setup:**

   ```bash
   cd backend
   npm install
   # Create a .env file with your credentials (MongoDB URI, JWT secret, Cloudinary keys)
   npm run dev
   ```

3. **Frontend setup:**

   ```bash
   cd ../frontend
   npm install
   npm start
   ```

---------------------------------------------------------------------------------------------------------------------

## 🧪 Environment Variables

Make sure to create a `.env` file in the backend folder with the following:

```env
PORT=provide a port number like 5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development(for developmet)/production(for deployment)
```

---------------------------------------------------------------------------------------------------------------------

## 🙌 Acknowledgements

* [Socket.IO](https://socket.io/)
* [Cloudinary](https://cloudinary.com/)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
* [React Hot Toast](https://react-hot-toast.com/)

---------------------------------------------------------------------------------------------------------------------
