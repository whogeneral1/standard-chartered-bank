# 🌐 Standard Chartered Bank – Digital Platform

This is a modern web-based digital banking platform designed for individuals and crypto users. Built with **Next.js 14**, **MongoDB**, and **Tailwind CSS**, it supports virtual cards, wallet transfers, FX conversion, KYC verification, and more.

---

## 💡 Core Features

- ✅ User Login / Signup (including Google OAuth)
- 👤 KYC/Verification Uploads
- 💰 Multi-wallet (Main & Savings)
- 🔁 Internal & External Transfers
- 💳 Virtual Card Management
- 🌐 Crypto-to-Wallet Conversion
- 🛠 Admin Panel with Tools
- 📩 Email Notifications
- 🧾 Full Transaction History with Filters

---

## 🛠 Tech Stack

- **Frontend:** Next.js 14, Tailwind CSS, Shadcn UI
- **Backend:** Node.js, MongoDB, Mongoose
- **Auth:** NextAuth (Google OAuth)
- **Deployment:** Vercel
- **Email:** Resend (or SendGrid ready)

---

## 🚀 Getting Started

### Clone & Setup
```bash
git clone https://github.com/whogeneral1/standard-chartered-bank.git
cd standard-chartered-bank
cp .env.production .env.local
npm install
npm run dev
