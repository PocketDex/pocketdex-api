# 🧠 PocketDex API

This is the backend API and database service for PocketDex — the competitive companion app for Pokémon TCG Pocket tournaments.

## Features
- Supabase schema (auth, players, matches, tournaments)
- Edge functions or Express endpoints
- Card scraper from LimitlessTCG
- Deck upload + OCR (Google Vision)
- Trust system, XP logic, badge sync

## Tech Stack
- Supabase (PostgreSQL, Auth, Storage)
- Node.js / TypeScript (Edge Functions)
- GitHub Actions (data sync, cron jobs)
- Optional Firebase (for messaging)

## Local Setup
```bash
git clone https://github.com/PocketDex-GG/pocketdex-api
cd pocketdex-api
pnpm install
pnpm dev
```

## License
MIT
