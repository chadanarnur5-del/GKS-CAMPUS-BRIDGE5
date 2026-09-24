# GKS Campus Bridge

A Next.js + TypeScript starter for the GKS Campus Bridge concept.

## Run

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Deploy

The project can be imported into Replit, opened in Bolt/StackBlitz, pushed to GitHub, and deployed on Vercel. The same source structure is used across these environments.

## Important

This starter intentionally uses localStorage for a small amount of demo state. It does **not** pretend to implement live GKS data, maps, AI, authentication, document storage, or emergency data. For production, connect Supabase/PostgreSQL, an AI provider through server-side routes, and a licensed map/place provider. Verify official GKS/immigration/university sources and show source + last-updated metadata.

## Security

Never commit real API keys. Never place private keys in `NEXT_PUBLIC_*` variables. Add authentication, row-level authorization, secure storage, file validation, rate limiting, audit logging and consent flows before handling real student documents.
