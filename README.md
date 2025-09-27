# 🤖 AI-Powered Mock Interview Platform (AI-MockCraft)

An interactive web application designed to help students and professionals practice interviews using **AI-generated questions** and **real-time feedback**.  
Built with **Next.js, React, TailwindCSS, and AI integration**, this platform simulates interview scenarios to boost confidence and performance.

## 🚀 Features
- 🎤 **AI-Generated Interview Questions** – Dynamic, role-specific question sets.
- 📝 **Real-Time Feedback** – Structured tips for improvement after each response.
- 🔐 **User Authentication** – Secure login with personalized interview sessions.
- 🎯 **Role-Based Access** – Custom interview experiences for different user types.
- 📊 **Performance Tracking** – Analyze past interviews and monitor progress.
- 💻 **Responsive UI** – Clean, interactive design with React & TailwindCSS.

## 🛠️ Tech Stack
- **Frontend:** Next.js, React, TailwindCSS  
- **Backend:** Node.js, API routes  
- **Database:** Drizzle ORM, PostgreSQL / MySQL  
- **AI Integration:** Gemini AI (for generating & evaluating questions)  
- **Other Tools:** Git, Vercel (deployment)  

## ⚡ Installation & Setup

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Ruchika-6004/AI-Mock-Interview-Web-Application.git
cd AI-Mock-Interview-Web-Application
````

### 2️⃣ Install Dependencies

Make sure you have **Node.js (>=18)** and **npm** installed. Then run:

```bash
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env.local` file in the root directory and add the following keys:

```env
# Example (update with your actual credentials)
DATABASE_URL=your_database_connection_string
NEXTAUTH_SECRET=your_secret_key
AI_API_KEY=your_gemini_api_key
```

### 4️⃣ Database Setup

If you’re using **Drizzle ORM**, run migrations:

```bash
npx drizzle-kit generate
npx drizzle-kit push
```

### 5️⃣ Run the Development Server

Start the server:

```bash
npm run dev
```

The app will be live at:

```
http://localhost:3000
```

### 6️⃣ Build for Production (Optional)

```bash
npm run build
npm start
```
🌐 Deployment (Vercel)

This project is easily deployable on Vercel. Follow these steps:

Push your project to GitHub.
Go to Vercel Dashboard.
Click New Project → Import your GitHub repository.
Set environment variables in Vercel Project Settings → Environment Variables (same as .env.local).
Click Deploy 🚀
Deployed Succesfully 

## 🚀 Live Demo

Check out the live deployed application here:  
👉 [AI Mock Interview Web Application](https://ai-mock-interview-web-application-n110dko2v.vercel.app)

---

## 📸 Screenshots
Landin Page:-<img width="1901" height="885" alt="Screenshot 2025-09-27 122813" src="https://github.com/user-attachments/assets/e1c308dc-60c9-46aa-b1e1-72f196cc6cda" />
DashBoard:-<img width="1912" height="888" alt="Screenshot 2025-09-27 122825" src="https://github.com/user-attachments/assets/9fe80198-aceb-4e59-8094-fd390cf1a579" />
About Us:- <img width="1895" height="864" alt="Screenshot 2025-09-27 122836" src="https://github.com/user-attachments/assets/661ba31e-c5f8-469e-8cbb-52468b218fdf" />

---

## 🎯 Project Duration

**Jul 2024 – Aug 2024**
Developed as part of the **Sobhasaria Group of Institutions** initiative.

---
## 📌 About
This project is part of **AI-MockCraft**, built to help learners prepare efficiently for interviews by simulating real-world scenarios.
It combines **full-stack development skills** with **AI-powered enhancements** to deliver an engaging experience.

---

## 👩‍💻 Author

**Ruchika**
📍 Sikar, Rajasthan
* 🌐 [LinkedIn](https://www.linkedin.com/in/ruchika)
* 💻 Aspiring Software Engineer | Full-Stack Developer

---

## 🤝 Contributors

Special thanks to the team members who contributed to this project:

* **Bhavana Saini** – Frontend & UI Enhancements
* **Shoab Khan** – Backend & Database Integration

