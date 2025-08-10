# 🚗 AI Car Site

An AI-powered car listing platform built with **Next.js**, **TypeScript**, **Tailwind CSS**, and **Prisma**.

## 📌 Features
- AI-powered car search
- User authentication (Google OAuth, NextAuth.js)
- Car listings with detailed specifications
- Contact forms and booking test drives
- Fully responsive UI

## 🛠 Tech Stack
- **Frontend:** Next.js, TypeScript, Tailwind CSS
- **Backend:** Next.js API routes, Prisma ORM
- **Database:** PostgreSQL
- **Authentication:** NextAuth.js
- **AI:** Integrated AI actions for smart search

## 📂 Project Structure
ai-car-site/
├── prisma/ # Database schema and migrations
├── src/ # Application source code
├── public/ # Static assets
├── .env # Environment variables (DO NOT COMMIT REAL VALUES)
├── package.json # Project dependencies
└── README.md # Project documentation

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Achalnawal2745/ai-car-site.git
cd ai-car-site
2. Install dependencies


npm install
3. Configure environment variables
Create a .env file and fill it with your credentials:

GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
DATABASE_URL=your-database-url
NEXTAUTH_SECRET=your-secret
4. Run database migrations

npx prisma migrate dev
5. Start the development server

npm run dev
