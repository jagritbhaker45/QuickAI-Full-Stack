QuickAI – AI SaaS Platform

QuickAI is a production-ready AI SaaS platform built using the PERN stack (PostgreSQL, Express.js, React.js, Node.js) with Clerk authentication, Stripe subscription billing, and a Neon serverless database.

It provides a suite of AI-powered tools for content creation, image processing, and document analysis.

Key Features
Authentication

Secure sign-in/sign-up

Profile management

Session handling via Clerk

Subscription Billing

Monthly premium plans

Stripe integration with webhook handling

Database

Serverless PostgreSQL using Neon

Scalable and deployment-friendly

AI Tools Included

Article Generator – generate long-form content

Blog Title Generator – create titles from keywords

AI Image Generator – generate images from prompts

Background Remover – remove backgrounds instantly

Object Remover – delete unwanted objects from images

Resume Analyzer – AI-powered resume insights

Tech Stack
Category	Technologies
Frontend	React.js, Tailwind CSS
Backend	Node.js, Express.js
Database	PostgreSQL (Neon Serverless)
Authentication	Clerk
Payments	Stripe Subscriptions
AI Models	Google Gemini, OpenAI, Stability
Deployment	Vercel (Frontend), Render/Railway (Backend), Neon (DB)
Live Demo

🔗 https://quick-ai-one-coral.vercel.app/

Screenshot

My Contributions

Designed backend architecture with Express.js

Integrated Gemini, OpenAI, and Stability APIs

Implemented Stripe subscription flow + webhooks

Added Clerk authentication and route protection

Built UI interfaces using React + Tailwind

Configured Neon PostgreSQL

Added usage limits and premium access logic
Setup Instructions
1. Clone the repo
git clone https://github.com/jagritbhaker45/QuickAI-Full-Stack.git
cd QuickAI-Full-Stack

2. Install dependencies
npm install

3. Add environment variables

Create a .env file:

CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
STRIPE_KEY=
STRIPE_WEBHOOK_SECRET=
OPENAI_API_KEY=
GEMINI_API_KEY=
STABILITY_API_KEY=
DATABASE_URL=

4. Run the app
npm run dev

Author

Jagrit Bhaker
M.Tech in Computer Science
Full-Stack Developer | AI & Web Development Enthusiast
📧 Email: jagritbhaker45@gmail.com
