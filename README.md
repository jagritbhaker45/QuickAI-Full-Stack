# QuickAI – AI SaaS Platform

QuickAI is a production-ready AI SaaS platform built using the **PERN stack** (PostgreSQL, Express.js, React.js, Node.js) with Clerk authentication, Stripe subscription billing, and a Neon serverless database.

It provides a suite of AI-powered tools for content creation, image processing, and document analysis.

---

## Key Features

### Authentication (Clerk)
- Secure sign-in / sign-up
- Profile management
- Session handling and protected routes

### Subscription Billing (Stripe)
- Monthly premium plans
- Webhook-based subscription verification
- Access control based on subscription state

### Database (Neon)
- Serverless PostgreSQL
- Fast, scalable, cloud-native

### AI Tools Included
- **Article Generator** – generate long-form content
- **Blog Title Generator** – create titles from keywords
- **AI Image Generator** – generate images from prompts
- **Background Remover** – remove image backgrounds
- **Object Remover** – remove unwanted objects from images
- **Resume Analyzer** – AI-powered resume analysis & insights

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
| Deployment      | Vercel (Frontend), Render or Railway (Backend)  |

---

## Live Demo

https://quick-ai-one-coral.vercel.app/

---

## Screenshot

> Put the screenshot file in your repository (recommended path: `/assets/screenshot.png`) and use the relative path below.
>
> If you use an external host for images, ensure the URL is correct and reachable.

![QuickAI Screenshot](/assets/screenshot.png)

---

## My Contributions

- Designed backend architecture with Express.js and PostgreSQL
- Integrated Gemini, OpenAI, and Stability APIs for text and images
- Implemented Stripe subscription flow with webhooks and access control
- Added Clerk authentication and protected routes
- Built front-end UI using React + Tailwind CSS
- Configured Neon PostgreSQL and optimized database queries
- Implemented request batching and rate-limiting for AI API calls

---

## Local Setup

1. Clone the repository:
```bash
git clone https://github.com/jagritbhaker45/QuickAI-Full-Stack.git
cd QuickAI-Full-Stack
Install dependencies:

npm install


Create a .env file in the repo root and add required variables:

CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
STRIPE_KEY=
STRIPE_WEBHOOK_SECRET=
OPENAI_API_KEY=
GEMINI_API_KEY=
STABILITY_API_KEY=
DATABASE_URL=


Start the project:

npm run dev

Future Improvements

Add Retrieval-Augmented Generation (RAG) for context-aware responses

Convert backend into microservices for better scaling

Add analytics dashboard for usage metrics

Add team/workspace support and user management

Author

Jagrit Bhaker
M.Tech in Computer Science
Full-Stack Developer | AI & Web Development Enthusiast

Email: jagritbhaker45@gmail.com
