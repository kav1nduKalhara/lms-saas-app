🚀 SaaS App – Next.js, Supabase & Payments

A full-stack SaaS application built using Next.js, Supabase, Stripe, and Clerk Auth.
This project was developed by following the SaaS App Full Course 2025 tutorial and customizing it to fit my own workflow.

📌 Features

🔑 Authentication & Authorization with Clerk/Supabase

💳 Stripe-powered Billing & Subscriptions

🗂️ Database & API with Supabase

🧭 Protected Routes & Middleware

🖼️ Modern UI with Tailwind CSS

🧾 Session History & Bookmarks

🛡️ Error Tracking with Sentry

🏗️ Tech Stack

Framework: Next.js 14 (App Router)

Database: Supabase (Postgres + Auth)

Payments: Stripe

Auth: Clerk

UI: Tailwind CSS, Shadcn UI

⚙️ Getting Started
1. Clone Repo
   git clone https://github.com/your-username/saas-app.git
   cd saas-app

2. Install Dependencies
   npm install
# or
yarn install

3. Configure Environment Variables

Create a .env.local file and add:

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret

4. Run Locally
   npm run dev


App will be live at http://localhost:3000 🎉



