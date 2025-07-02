# 💳 FlowPay

A modern peer-to-peer payment and wallet management system for seamless digital transactions.

## 🌟 Overview

FlowPay is a cutting-edge P2P payment system that allows users to transfer funds and manage their digital wallets effortlessly. Built with modern technologies, it provides a sleek interface for sending money, adding funds, and tracking transactions.

## ✨ Features

- 🏦 **Add Funds** - Seamlessly add money through simulated bank pages (HDFC and Axis)
- 💸 **Send Money** - Transfer funds to other users instantly
- 📊 **Transaction History** - View comprehensive transaction records
- 💰 **Balance Tracking** - Monitor unlocked, locked, and total balance in real-time
- 🔐 **Secure Authentication** - Protected with NextAuth and JWT tokens
- 💎 **Transaction Limits** - Safe transfers up to ₹10,000 per transaction
- ✅ **Data Validation** - Robust validation with Zod schemas

## 🛠️ Tech Stack

- **Frontend:** ⚛️ Next.js • 🎨 TailwindCSS • 💫 Framer Motion
- **Backend:** 🚀 Next.js API
- **Database:** 🐘 PostgreSQL • 🔷 Prisma ORM
- **Authentication:** 🔑 NextAuth
- **State Management:** ⚡ Recoil
- **Tools:** 📦 Turborepo • 📘 TypeScript • 🐳 Docker
- **Deployment:** ▲ Vercel

## 🚀 Quick Start

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/Flowpay.git
cd Flowpay
```

2. **Install dependencies:**
```bash
npm install
```

3. **Environment setup:**
- Copy `.env.example` to `.env`
- Configure: `JWT_SECRET`, `NEXTAUTH_URL`, `DATABASE_URL`

4. **Database initialization:**
```bash
npm run db:migrate
npm run db:generate
```

5. **Start development:**
```bash
npm run dev
```

6. **Production build:**
```bash
npm run build
```

## 📁 Project Structure

```
📦 FlowPay
├── 📄 README.md
├── 📁 apps
│   ├── 🏦 Bank-WebHook
│   ├── 🏪 merchant-app
│   └── 👤 user-app
├── 🐳 docker
│   └── Dockerfile.user
├── 📦 packages
│   ├── 🗃️ db
│   ├── ⚙️ eslint-config
│   ├── 📊 store
│   ├── 🔧 typescript-config
│   └── 🎨 ui
├── tsconfig.json
└── turbo.json
```

## 📜 License

MIT License - Feel free to use and modify! 🎉
