## 📱 Chat App — Features & Tech Stack  

A real-time chat application built using the **MERN stack**, **Socket.io**, and modern UI libraries.


<p align="left">
  <img src="https://img.shields.io/badge/MongoDB%20Atlas-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB Atlas" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/DaisyUI-FF69B4?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="DaisyUI" />
  <img src="https://img.shields.io/badge/Zustand-FFB703?style=for-the-badge&logo=react&logoColor=black" alt="Zustand" />
  <img src="https://img.shields.io/badge/React%20Hot%20Toast-F87171?style=for-the-badge&logo=react&logoColor=white" alt="React Hot Toast" />
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" alt="Cloudinary" />
</p>


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
