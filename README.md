# 🛋️ AI E-commerce Platform

A full-stack furniture store with an AI shopping assistant, live inventory and an admin dashboard. Built with Next.js, TypeScript, Sanity, Clerk and Stripe.

![AI E-commerce Platform homepage](./screenshots/home.png)

🔗 **Live demo:** [ai-ecommerce-platform-three.vercel.app](https://ai-ecommerce-platform-three.vercel.app/)

## ✨ Features

**Shoppers**
- Browse and search furniture by category, material, colour and price
- Chat with an AI assistant that finds products and checks order status
- Persistent shopping cart with stock validation
- Secure checkout with Stripe
- Order history for signed-in users

**Admins**
- Dashboard with sales and inventory insights
- Create, edit and publish products
- Update order status (paid, shipped, delivered)
- Low-stock alerts

## 🛠️ Tech Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Sanity](https://img.shields.io/badge/Sanity-F03E2F?logo=sanity&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?logo=clerk&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

- **Frontend:** Next.js (App Router), React, TypeScript, Tailwind CSS, shadcn/ui
- **Content and data:** Sanity CMS
- **Authentication:** Clerk
- **Payments:** Stripe Checkout and webhooks
- **AI:** Vercel AI SDK with Claude
- **State:** Zustand
- **Hosting:** Vercel

## 🚀 Run It Locally

```bash
git clone https://github.com/mosesyogo/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
pnpm install
cp .env.example .env.local
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000).

### Environment variables

Add your own values to `.env.local` (never commit this file):

```
NEXT_PUBLIC_SANITY_PROJECT_ID=
NEXT_PUBLIC_SANITY_DATASET=
SANITY_API_WRITE_TOKEN=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
AI_GATEWAY_API_KEY=
```

## 🧠 What I Practised

- Building a full-stack app with the Next.js App Router
- Connecting authentication, a CMS and payments in one project
- Giving an AI assistant tools that respect who is signed in
- Handling Stripe webhooks to create orders and update stock
- Deploying and configuring a project on Vercel

## 👤 Author

**Moses Yogo**, Front-End Developer
[LinkedIn](https://www.linkedin.com/in/moses-yogo) · [GitHub](https://github.com/mosesyogo)