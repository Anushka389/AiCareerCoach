
# AI-Career-Coach 🧠💼

# Full Stack AI Career Coach with Next JS, Neon DB, Tailwind, Prisma, Inngest, Shadcn UI 

**AI-Career-Coach** is a full-stack, AI-powered career guidance web application that helps users enhance their job readiness. It provides personalized industry insights, AI-generated resume and cover letter builders, and mock interview preparation — all updated automatically every 10 days using serverless cron jobs.

## 🌐 Live Demo
       
👉 [View Demo on Edmo](https://edmo.ai/view/ai-career-coach-orpin-alpha.vercel.app)

> Replace the link above with your actual Edmo demo URL.

## 🚀 Features

- 🔐 User Authentication with custom login/sign-up
- 🎯 Personalized User Onboarding
- 🧠 AI-powered **Industry Insights** (updated every 10 days via Inngest cron jobs)
- 💬 **Mock Interview Questions** generator
- 📊 **Interview Performance Statistics**
- 📝 **AI Resume Builder** with Markdown and PDF download support
- 📄 **Cover Letter Generator**
- 🧑‍💼 Clean, modern UI with **Shadcn/UI** and responsive design

## 🛠 Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS, Shadcn/UI  
- **Backend**: Next.js API Routes, Inngest for background tasks and cron jobs  
- **Database**: PostgreSQL / Prisma ORM  
- **Authentication**: NextAuth  
- **AI Models**: Google Gemini API for career insights, interviews, and writing tasks  
- **Deployment**: Vercel / Any modern hosting platform  

## 📦 Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ai-career-coach.git
   cd ai-career-coach


## Install Dependencies

```bash
npm install


## Run devlopment Server
```bash
npm run dev


### **Make sure to create a `.env` file with following variables **-
```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```





          
 

