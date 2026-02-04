# Reddit Clone API (Express + Prisma + Postgres)

## Prerequisites
- Node.js 18+
- Postgres running locally

## Setup
```bash
cd backend
cp .env.example .env
npm install
npm run prisma:generate
npm run prisma:migrate
npm run dev
```

The API will start on `http://localhost:4000`.

## Endpoints
- `GET /health` — simple health check
