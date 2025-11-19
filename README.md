# QuickAI – AI SaaS Platform

QuickAI is a production-ready AI SaaS platform built using the PERN stack (PostgreSQL, Express.js, React.js, Node.js) with Clerk authentication, Stripe subscription billing, and a Neon serverless database.

It provides multiple AI-powered tools for content generation, image processing, and document analysis.

---

## Key Features

### Authentication (Clerk)
- Secure sign-in / sign-up
- Profile management
- Protected routes and session handling

### Subscription Billing (Stripe)
- Monthly premium plans
- Webhook-based subscription verification
- Access control for paid features

### Database (Neon)
- Serverless PostgreSQL
- Cloud-native scaling and performance

### AI Tools Included
- Article Generator – generate long-form content
- Blog Title Generator – create titles from keywords
- AI Image Generator – generate images from prompts
- Background Remover – remove image backgrounds
- Object Remover – remove unwanted objects from images
- Resume Analyzer – AI-powered resume insights

---

## Tech Stack

| Category        | Technologies                                    |
|-----------------|-------------------------------------------------|
| Frontend        | React.js, Tailwind CSS                          |
| Backend         | Node.js, Express.js                             |
| Database        | PostgreSQL (Neon Serverless)                    |
| Authentication  | Clerk                                           |
| Payments        | Stripe Subscriptions                            |
| AI Models       | Google Gemini, OpenAI, Stability                |
| Deployment      | Vercel (Frontend), Render/Railway (Backend)     |

---

## Live Demo

https://quick-ai-one-coral.vercel.app/

---

## Screenshots

### Home Page
<img width="1332" height="605" alt="Screenshot 2025-11-17 152942" src="https://github.com/user-attachments/assets/9a73e9ba-2ca1-4651-ab71-9289b177c54c" />


### Dashboard
<img width="1365" height="595" alt="Screenshot 2025-11-17 151757" src="https://github.com/user-attachments/assets/bfe1b3b4-5088-43da-bee0-46b4ee814487" />


### Article Generator Example
<img width="1332" height="605" alt="Screenshot 2025-11-17 152942" src="https://github.com/user-attachments/assets/bc1db59a-a65a-4592-9501-66e4ff4f3056" />



## My Contributions
- Designed backend architecture (Node.js + Express)
- Integrated Gemini, OpenAI, and Stability APIs
- Implemented Stripe subscription workflow with webhooks
- Added Clerk authentication and protected routes
- Built UI with React and Tailwind CSS
- Configured Neon PostgreSQL and optimized queries
- Implemented usage limits and access control for premium features

---

## Local Setup

1. Clone the repository
git clone https://github.com/jagritbhaker45/QuickAI-Full-Stack.git
cd QuickAI-Full-Stack

2. Install dependencies
npm install

3. Create a .env file and add the required keys
CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
STRIPE_KEY=
STRIPE_WEBHOOK_SECRET=
OPENAI_API_KEY=
GEMINI_API_KEY=
STABILITY_API_KEY=
DATABASE_URL=

4. Start the development server
npm run dev

Author

 Jagrit |
 M.Tech in Computer Science
 Full-Stack Developer | AI & Web Development Enthusiast

 Email: jagritbhaker45@gmail.com
