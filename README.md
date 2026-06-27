# Kvants Trading Terminal

Real-time trading interface for Hyperliquid — positions, orders, and AI-assisted execution.

## Stack
- **Framework:** Next.js 16 (App Router, Turbopack)
- **Styling:** Tailwind CSS
- **Hosting:** Vercel (staging → production)
- **Repo:** https://github.com/KvantsPlatform/trading-terminal

## Quick Start
```bash
npm install
npm run dev
```

## Environment Variables
- `NEXT_PUBLIC_HYPERLIQUID_API_URL` — Hyperliquid API endpoint
- `HYPERLIQUID_WALLET_ADDRESS` — Wallet for trading operations
- `HYPERLIQUID_PRIVATE_KEY` — Private key for signing (server-side only)
