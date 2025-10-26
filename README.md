# 🧭 Om Tours – AI-Powered Travel Itinerary Generator (Frontend)

Developed by **Hemant Verma** and Team *The Intelligent Squad*  
🏆 **1st Prize Winner – March Cohort AI Innovation Pitch Competition, CDC NIT Rourkela**

Om Tours is a modern AI-powered travel planner web application that generates **personalized, real-time itineraries** based on user preferences using the **Gemini API**.  
Built with **React + TypeScript + Vite**, it combines performance, simplicity, and intelligence for an enhanced travel planning experience.

---

## 📚 Table of Contents

- [📌 Overview](#-overview)
- [✨ Features](#-features)
- [🧠 AI Integration](#-ai-integration)
- [🛠️ Tech Stack](#-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🧩 Key Components](#-key-components)
- [🔐 Authentication Flow](#-authentication-flow)
- [🚢 Deployment](#-deployment)
- [🤝 Contribution](#-contribution)
- [📄 License](#-license)
- [🔗 Links](#-links)

---

## 📌 Overview

Om Tours is an intelligent travel itinerary generator that allows users to:
- Input trip details (destination, budget, duration, and purpose)
- Get AI-generated day-by-day plans with real-time adjustments  
- Modify, regenerate, and finalize itineraries interactively  

The system leverages **Gemini AI** for contextual suggestions, ensuring every trip is unique and efficient.  
The frontend is designed for **scalability**, **performance**, and **intuitive user experience**.

---

## ✨ Features

✅ AI-driven personalized itinerary generation  
🌤️ Real-time updates based on user feedback  
🧭 Explore mode to discover destinations and recommendations  
📅 Interactive day & time-slot-based planner  
🔁 Regenerate and finalize optimized travel plans  
🗺️ Google Maps integration for route and location visualization  
📱 Responsive and accessible user interface  

---

## 🧠 AI Integration

Om Tours uses **Google’s Gemini API** to:
- Understand user inputs in natural language  
- Generate tailored itineraries and recommendations  
- Rebuild plans dynamically based on user acceptance/rejection  
- Maintain contextual understanding across user sessions  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| ⚛️ **React + TypeScript** | Frontend architecture & UI components |
| ⚡ **Vite** | High-performance build tool |
| 🧠 **Gemini API** | AI itinerary generation |
| 🌐 **Axios** | API communication |
| 🔐 **React Router DOM** | Client-side routing |
| 🎨 **CSS + Lucide React** | Styling & icons |
| 🔔 **React Hot Toast** | Instant notifications |

---

## 📁 Project Structure

src/
┣ components/
┃ ┣ HomePage.tsx
┃ ┣ Planner.tsx
┃ ┣ Auth/
┃ ┃ ┣ LoginPage.tsx
┃ ┃ ┗ SignUpPage.tsx
┣ context/
┃ ┗ authUser.ts
┣ utils/
┃ ┗ geminiAI.ts
┣ App.tsx
┗ main.tsx


---

## 🚀 Getting Started

### 📦 Prerequisites
- Node.js `v16+`
- npm or yarn

### 🧭 Installation

```bash
git clone https://github.com/Hemant-Verma-IND/Om-Tours-Frontend.git
cd Om-Tours-Frontend
npm install


▶️ Run Locally
npm run dev


Open in browser → http://localhost:5173

🏗️ Build for Production
npm run build

👀 Preview Build
npm run preview

🧩 Key Components

App.tsx – Root component & route setup

HomePage.tsx – Landing page with destination discovery

Planner.tsx – Interactive AI itinerary generator

LoginPage / SignUpPage – Authentication interface

SearchPage.tsx – Filter & search experiences

Footer.tsx – App-wide footer

🔐 Authentication Flow

Managed globally via authUser.ts context

Protected routes for itinerary and history pages

Redirection to login/signup for unauthenticated users

Auto-check for auth state on app load

🚢 Deployment

🚀 Live on Vercel
https://om-tours-iota.vercel.app/

🤝 Contribution

Contributions are welcome!

git checkout -b feature/new-feature
git commit -m "Add new feature"
git push origin feature/new-feature


Open a Pull Request 🚀

📄 License

📝 MIT License – Free to use and modify.

🔗 Links

🌐 Live Demo: [Coming Soon on Vercel]
📦 GitHub Repository: [Om-Tours-Frontend](https://github.com/Hemant-Verma-IND/Om-Tours-Frontend.git)
