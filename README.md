# 🤖 Resume Builder — Full Stack AI Resume Builder (MERN + Gemini + ImageKit)

![Resume Screenshot](./client/src/assets/resume.png)

Resume Builder is a full-stack AI-powered Resume Builder application built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
It allows users to **create, preview, share, and optimize resumes using AI**, manage multiple templates, and upload images with background removal.  
The app integrates **Google Gemini AI** for resume optimization and **ImageKit** for storing profile images.

---

## 🧠 Features

- 🔐 **User Authentication (Sign up / Sign in)**
- 📝 **Create New Resume with multiple templates**
- 👀 **Live Preview & Shareable Link for resumes**
- 🤖 **AI Resume Optimization using Google Gemini**
- 🖼️ **Upload & Edit Images with background removal**
- ✏️ **Manage Resume (Add, Edit, Delete)**
- 💻 **Responsive Frontend built using React + Tailwind CSS**
- 📦 **MongoDB Database for storing resumes and user data**
- ⚡ **Express.js Backend with secure API routes**

---

## 💻 Tech Stack

| Technology                                                                                                     | Description                                              |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| ![React.js](https://img.shields.io/badge/React.js-61DAFB?style=flat&logo=react&logoColor=black)                | Frontend library for building dynamic and interactive UI |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white) | Utility-first CSS framework for responsive UI design     |
| ![Prebuilt UI](https://img.shields.io/badge/Prebuilt_UI-FF69B4?style=flat)                                     | Ready-to-use UI components to speed up development       |
| ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)                         | Frontend build tool for faster development               |
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)                | JavaScript runtime for backend                           |
| ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)          | Web framework for building API routes                    |
| ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)                | NoSQL database for storing resumes and user data         |
| ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat&logo=mongoose&logoColor=white)             | ODM library for MongoDB                                  |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)                      | HTTP client for frontend-backend communication           |
| ![BcryptJS](https://img.shields.io/badge/BcryptJS-3385FF?style=flat)                                           | Password hashing & encryption                            |
| ![CORS](https://img.shields.io/badge/CORS-FFB400?style=flat)                                                   | Middleware for cross-origin requests                     |
| ![Dotenv](https://img.shields.io/badge/Dotenv-000000?style=flat)                                               | Manage environment variables                             |
| ![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)                  | Token-based authentication                               |
| ![ImageKit](https://img.shields.io/badge/ImageKit-1D1D1D?style=flat&logo=imagekit&logoColor=00D9FF)            | Cloud image optimization & background removal            |
| ![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat&logo=google&logoColor=white)     | AI model for resume improvement and optimization         |

---

## 🚀 Features

| Feature                              | Description                                                                                      |
| ------------------------------------ | ------------------------------------------------------------------------------------------------ |
| 🔐 **User Authentication**           | Secure user signup, login, and JWT-based authentication with password hashing using **bcryptjs** |
| 📝 **Create New Resume**             | Build resumes using multiple templates with full customization                                   |
| 👀 **Live Preview & Shareable Link** | See resume changes in real-time and generate shareable links                                     |
| 🤖 **AI Resume Optimization**        | Improve and optimize resumes automatically using **Google Gemini AI**                            |
| 🖼️ **Upload & Edit Images**          | Add images to resumes and remove backgrounds using **ImageKit**                                  |
| ✏️ **Manage Resume**                 | Add, edit, and delete resumes easily                                                             |
| 💻 **Responsive Frontend**           | Clean and interactive UI built with **React.js** and **Tailwind CSS**                            |
| 📦 **MongoDB Database**              | Store resumes, templates, and user data securely                                                 |
| ⚡ **Express.js Backend**            | Secure REST API routes for all frontend interactions                                             |
| 🌐 **Environment Configuration**     | Manage API keys, MongoDB URI, and AI service keys securely using `.env`                          |
| ☁️ **Deployment Ready**              | Fully deployable MERN stack app with environment variables and production configurations         |

---

## 🗂️ Folder Structure

```
resume-builder/
│
├── client/ # Frontend (React.js)
│ ├── public/ # Static assets (favicon, logos, etc.)
│ ├── src/ # Source code
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page components (Home, Dashboard, Resume, etc.)
│ │ ├── assets/ # Images and icons
│ │ ├── App.jsx # Main App component
│ │ └── main.jsx # Entry point
│ ├── package.json # Frontend dependencies
│ └── vite.config.js # Vite config
│
├── server/ # Backend (Node.js + Express)
│ ├── configs/ # Config files (DB, AI, ImageKit, multer)
│ ├── controllers/ # Controllers (Resume, User, AI)
│ ├── middlewares/ # Middleware (auth)
│ ├── models/ # MongoDB models (Resume, User)
│ ├── routes/ # API routes
│ ├── server.js # Main server file
│ ├── package.json # Backend dependencies
│ └── node_modules/ # Installed node packages
│
├── README.md # Project documentation
└── .gitignore # Git ignored files
```

## 🏁 Getting Started

Follow these steps to run the project locally:

1. **Clone the repository:**

```
git clone https://github.com/singhayush007/RESUME_BUILDER.git
```

2. **Navigate to the project folder:**

```
cd RESUME_BUILDER
```

3. **Install dependencies:**

```
npm install
```

4. **Create a .env.local file in the root and add your environment variables:**

```
# MongoDB URI
MONGODB_URI=your_mongodb_connection_uri

# Gemini AI Key
GEMINI_API_KEY=your_gemini_api_key

# ImageKit Keys
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

5. **Run the development server and client:**

```
cd client : npm run dev
cd server : npm run server
```

6. **Open the app in your browser:**

```
http://localhost:5173
```

## 💻 Deployment

You can deploy this app using Vercel, Docker, or any Node.js hosting platform.

## 📄 License

This project is licensed under the MIT License — feel free to use and modify it as per your needs.
