# 🎯 Prepy-AI – AI-Powered Resume & Interview Prep Assistant

[Live Demo 🌐](https://prepy-ai.vercel.app)

Prepy-AI is a smart career assistant built to help professionals **land their dream jobs** by automating the creation of tailored **resumes**, **cover letters**, **industry insights**, and **profession-specific MCQ quizzes** using Google's **Gemini API**.

Built with the modern web stack: **Next.js App Router**, **Clerk for authentication**, **Neon/PostgreSQL**, and styled beautifully with **ShadCN UI** and **Tailwind CSS**.

---

## 🚀 Features

### ✍️ AI Resume & Cover Letter Generator  
Crafts job-ready resumes and cover letters using your:
- Skills
- Job description
- Career goals

### 🎯 AI Interview MCQ Quiz  
Dynamically generates personalized multiple-choice questions based on your:
- Profession
- Role or domain expertise  
(All powered by Gemini API)

### 🧭 Industry Suggestions  
Based on your background, the AI recommends industries best aligned with your skill set.

### 🔐 Secure Authentication with Clerk.dev  
Modern and secure login/sign-up flows with session handling.

### 🖼️ Clean UI with ShadCN Components  
Elegant and responsive UI using prebuilt components with Tailwind CSS.

---

## 🛠 Tech Stack

| Tech               | Purpose                             |
|--------------------|-------------------------------------|
| **Next.js App Router** | Fullstack framework (Pages + APIs) |
| **Clerk.dev**      | Authentication and user sessions    |
| **PostgreSQL (Neon)** | Cloud-hosted relational DB        |
| **Prisma ORM**     | Type-safe database client           |
| **Google Gemini API** | Generative AI for content creation |
| **ShadCN UI**      | UI components (based on Radix UI)   |
| **Tailwind CSS**   | Utility-first CSS styling           |
| **Vercel**         | Hosting & CI/CD                     |

---

## ⚙️ Environment Setup

### 📁 Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/prepy-ai.git
cd prepy-ai
```
---
##  Install Dependencies
```bash
npm install
```
---
##  Local Development Instructions

### Create .env
```bash
# PostgreSQL (Neon DB)
DATABASE_URL=your_neon_postgresql_url

# Clerk Authentication Keys
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Clerk Routing URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Google Gemini API
GEMINI_API_KEY=your_google_gemini_api_key
```
---
## Set Up the Database
```bash
npx prisma generate
npx prisma db push
```
---
### Run the Development Server
```bash
npm run dev
```
---
## Packages & Tools Used

### Clerk Authentication
```bash
npm install @clerk/nextjs
```
### Prisma + Neon PostgreSQL
```bash
npm install prisma @prisma/client
npx prisma init
```
### ShadCN UI + Tailwind
```bash
npx shadcn-ui@latest init
```
### Gemini AI SDK
```bash
npm install @google/generative-ai
```
---
## 🚀 Deployment on Vercel
- Push your code to GitHub

- Go to vercel.com

- Import the GitHub repo

- Set all environment variables in Project Settings → Environment Variables

- Click Deploy

---
## 🧠 Example Use Cases
- A fresh graduate generates job-specific resumes for multiple roles

- A software engineer prepares for interviews with tailored MCQs

- A marketing professional discovers industry shifts and new roles

---
## 📄 License
MIT License © 2025 Prepy-AI by Your Name
