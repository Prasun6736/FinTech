# 💰 FinTech – Personal Finance Tracker

**FinTech** is a modern **personal finance tracker** that allows users to create accounts, track expenses, and manage transactions efficiently.  
Designed for simplicity and security, it supports smart features like **receipt scanning**, **real-time updates**, and **automated transaction handling**.

With FinTech, staying in control of your finances is easier than ever — whether you're managing personal spending or monitoring financial habits over time.

---

## 🔑 Key Features

- ✅ Create an account with secure authentication  
- 📊 Add & view expenses with categorization  
- 🧾 Scan receipts to auto-log transactions  
- 🔁 Handle multiple concurrent transactions  
- 🔐 Robust backend security architecture  
- 🌗 Dark/light mode support  

---

## 🛠️ Tech Stack

| Technology      | Purpose                                                                 |
|-----------------|-------------------------------------------------------------------------|
| **Next.js**     | Frontend & API routes using the App Router                              |
| **PostgreSQL**  | Relational database to store users, expenses, and transactions          |
| **Prisma**      | ORM to interact with PostgreSQL in a type-safe way                      |
| **Inngest**     | Handles async workflows like scanning receipts and processing payments  |
| **Arcjet**      | API-level security, rate limiting, and bot protection                   |
| **Tailwind CSS**| Utility-first CSS framework for UI styling                              |

---

## ⚙️ Use Cases

- **PostgreSQL**: Used to store and manage all user data, financial records, and transaction history.
- **Prisma**: Provides a clean and safe way to interact with the PostgreSQL database using models and migrations.
- **Inngest**: Runs background jobs and handles processes like scanning receipts and processing batch transactions.
- **Arcjet**: Secures API endpoints with protections like rate limiting and bot prevention.
- **Next.js**: Handles routing, UI rendering, API logic, and server-side processing.

---

## 🎥 Demo Video

📽️ **Watch the Demo**  
[![FinTech Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

---

## 🚀 Getting Started (Local)

```bash
# Clone the repo
git clone https://github.com/yourusername/fintech-tracker.git
cd fintech-tracker

# Install dependencies
npm install

# Copy environment variables
add env variables

# Run Prisma
npx prisma generate

# Start the app
npm run dev
