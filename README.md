# Hi, I'm Sollid 👋

**Full-stack & Web3 developer** building production-style web apps with TypeScript, Next.js and Supabase, and on-chain systems with Solidity and Foundry.

I like hard boundaries in software: row-level security instead of trust, on-chain policy instead of hot keys, and UIs that tell users exactly what will happen before they sign.

## Featured projects

### [WOLV Spot Lens](https://github.com/sollid-web/wolv-stock) · [live](https://www.wolv.space)
Tokenized-stock discovery and price-gap monitor on BNB Smart Chain. Compares issuer reference prices with executable on-chain quotes, normalizes them per underlying share, flags stale quotes and market-session mismatches, and hands off to a user-authorized wallet trade.
`Next.js` `TypeScript` `Supabase` `wagmi/viem` `Foundry` · 460+ commits · BNB Chain Tokenized Stocks hackathon

### [TapeGuardian](https://github.com/sollid-web/tapeguard) · [live demo](https://tapeguard.tapeguard.workers.dev)
Autonomous trading agent that never holds a private key. Funds sit in a keyless `AgentContainer`; every trade must pass an on-chain `PolicyCircuit` (per-trade caps, daily caps, whitelisted router and function selectors, pause switch) in the same atomic call.
`Solidity` `Foundry` `Cloudflare Workers` `X Layer` · 16 Foundry regression tests

### [EstatelQ](https://github.com/sollid-web/leadforge)
Multi-tenant real-estate lead-routing SaaS MVP. Organizations, manager/agent roles, approval-gated lead reveals, Stripe-confirmed paid unlocks, AES-256-GCM encryption of contact data, full audit logging, and RentCast / OpenStreetMap integrations.
`Next.js` `TypeScript` `Supabase RLS` `Stripe` `Resend` `Zod`

### [Logistics Platform](https://github.com/radical-workspace/logistics-platorm)
Shipment-tracking platform with a customer dashboard, admin console, realtime shipment updates over Supabase Realtime, and a live tracking map.
`Next.js` `React 19` `Tailwind v4` `Supabase Realtime` `MapLibre` `Playwright`

### In progress
- **[Latch](https://github.com/sollid-web/latch)**: savings agent for X Layer where a 13-gate NAND circuit decides whether each USDT sweep is allowed. (`Solidity` `ERC-6551` `React`)

## Tech stack

**Languages:** TypeScript, JavaScript, Solidity, Python, SQL
**Frontend:** React, Next.js (App Router), Tailwind CSS
**Backend & data:** Node.js, Next.js API routes, Supabase (Postgres, Auth, RLS, Realtime)
**Web3:** Foundry, wagmi, viem, BNB Smart Chain, X Layer
**Infra & tooling:** Vercel, Cloudflare Workers, GitHub, Playwright, Stripe, Resend

## Contact

- GitHub: [@sollid-web](https://github.com/sollid-web)
