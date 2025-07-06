## 📱 Chat App — Features & Tech Stack  

A real-time chat application built using the **MERN stack**, **Socket.io**, and modern UI libraries.

---

### 🚀 Tech Stack  

- **MongoDB Atlas (Cluster)** — Cloud-based NoSQL database  
- **Express.js** — Backend framework for Node.js  
- **React.js** — Frontend library for building interactive UIs  
- **Node.js** — JavaScript runtime environment  
- **Socket.io** — Real-time, bi-directional communication  
- **Tailwind CSS + DaisyUI** — Utility-first and component-based CSS frameworks  
- **Zustand** — Lightweight global state management  
- **Axios** — Promise-based HTTP client  
- **React Hot Toast** — Notification system for user feedback  
- **Cloudinary** — Image optimization and media management  

---

### 📌 Features  

✅ **Authentication & Authorization** — Secure login/register with **JWT**  
✅ **Real-time Chat** — Instant bi-directional messaging with **Socket.io**  
✅ **Online User Status** — Dynamic presence detection stored in **MongoDB Cluster**  
✅ **Global State Management** — Efficient app-wide state with **Zustand**  
✅ **Image Upload & Optimization** — Seamless media handling with **Cloudinary**  
✅ **HTTP Requests** — API interaction via **Axios**  
✅ **User Action Feedback** — Interactive notifications using **React Hot Toast**  
✅ **Clean & Responsive UI** — Built with **Tailwind CSS** and **DaisyUI**  

---

### ⚙️ Environment Variables Setup (`.env`)

Create a `.env` file in the root directory and configure the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
