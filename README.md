Structureure
# 🎮 GameHub — Full-Stack Gaming Website

GameHub is a modern full-stack web application for hosting simple games,
leaderboards, user profiles, and real-time chat.

---

## 🚀 Features

- **Next.js 13** frontend with React & TailwindCSS
- **Authentication** with NextAuth (Credentials + GitHub)
- **PostgreSQL + Prisma ORM**
- **Real-time chat** using Socket.IO
- **Leaderboard system** with top scores
- **Docker support** for easy setup
- **Role-based access** (User / Admin)

---

## 📂 Project Stru

gaming-website/ ├── docker-compose.yml ├── Dockerfile ├── prisma/ │   ├── schema.prisma │   └── seed.ts ├── src/ │   ├── pages/ │   │   ├── index.tsx │   │   ├── games/[id].tsx │   │   ├── leaderboard.tsx │   │   ├── profile.tsx │   │   ├── api/ │   │   │   ├── auth/[...nextauth].ts │   │   │   ├── games.ts │   │   │   ├── leaderboard.ts │   │   │   └── chat.ts │   ├── components/ │   │   ├── Layout.tsx │   │   ├── GameCard.tsx │   │   └── ChatBox.tsx │   ├── lib/ │   │   ├── prisma.ts │   │   └── auth.ts ├── public/ │   └── game-covers/ ├── tailwind.config.js ├── package.json └── README.mdcture
