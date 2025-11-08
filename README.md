# DevAI Chatbot 💬

A full-stack MERN AI chatbot application powered by the Google Gemini API. Users can log in, hold conversations with an intelligent assistant, and have their chat history saved to their account.

## 🚀 Live Demo

**Check out the live site:** **[https://devai-amber.vercel.app/](https://devai-amber.vercel.app/)**

## ✨ Key Features

* **Google Gemini API:** Integrates with the latest Google Gemini model for fast and intelligent responses.
* **Dual Authentication:** Users can sign in using two methods:
    * Email OTP (via Nodemailer)
    * Google Auth (via Firebase)
* **Full Chat CRUD:** Users can create new chat sessions and delete old ones.
* **Saved Conversations:** All messages are saved to a MongoDB database, allowing users to pick up where they left off.
* **Modern, Responsive UI:** Built with React and Tailwind CSS for a clean and responsive experience on all devices.

## 💻 Tech Stack

### Frontend
* **React (Vite)**
* **React Context API** (for state management)
* **Tailwind CSS**
* **Firebase** (for Google client-side auth)
* **Axios**

### Backend
* **Node.js**
* **Express**
* **MongoDB** (with Mongoose)
* **JWT (JSON Web Tokens)**
* **Nodemailer** (for OTP email)

## 🌐 Deployment

* **Frontend:** Deployed on **Vercel**.
* **Backend:** Deployed on **Render**.
