# 🦊 HR Projects API (Elysia + Bun + Supabase + Prisma)

> Minimal, fast, and production-ready backend API for HR tools using Elysia on Bun.

## ✨ Features

⚡ Elysia + Bun – Ultra-fast TypeScript-first backend framework
🔑 JWT Auth – Secure authentication with cookie-based session
🗄️ Supabase – Simple database access and REST-like query
🛠️ Prisma – Type-safe ORM for advanced data modeling
🧩 Modular Architecture – Clean separation of routes, controllers, services, and middleware
✅ TypeScript Support – Strongly typed API with interfaces

## 🚀 Getting Started
### 1. Clone the repo
```bash
git clone https://github.com/untitlez/HR-Projects-API.git
cd HR-Projects-API
```

### 2. Install dependencies
```bash
bun install
```

### 3. Setup environment variables
Create a .env file in the root folder:
```env
NODE_ENV=development
DOMAIN=http://localhost:5173
JWT_SECRET=your_jwt_secret_key

SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 4. Start the development server
```bash
bun run dev
```

### 5. Open in browser / API client
```plaintext
http://localhost:5000
```

## 🧱 Project Structure
```plaintext
/src
├── index.ts              
│
├── controllers/          
│   ├── auth.ts           
│   └── users.ts          
│
├── services/             
│   ├── auth.ts
│   └── users.ts
│
├── middleware/           
│   └── auth.ts
│
├── db/                   
│   └── supabase.ts       
│
├── prisma/               
│   └── schema.prisma
│
├── routes/               
│   └── index.ts
│
├── interface/            
│   ├── auth.ts
│   └── users.ts
│
└── .env                  
```
