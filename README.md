# InterviewAI

> AI interview preparation and coaching

## Features
- Mock interviews
- Answer frameworks
- Company research
- Salary negotiation
- Feedback analysis

## Stack
- Next.js 14 (App Router) + TypeScript
- Tailwind CSS
- OpenAI GPT-4o-mini
- Stripe Subscriptions
- Vercel deployment

## Quick Start

```bash
npm install
cp .env.example .env.local
# Fill in API keys
npm run dev
```

## Pricing
| Plan | Price |
|------|-------|
| Free | $0/mo |
| Pro  | $19/mo or $159/yr |

## Deployment
### Vercel
1. Push to GitHub.
2. Import the repository in Vercel.
3. Add environment variables.
4. Deploy from `main`.

### CI
`.github/workflows/ci.yml` runs script-aware checks:
- npm install (`ci` when lockfile exists)
- `lint`, `test`, and `build` only when scripts exist

## Environment Variables
Configure (from `.env.example`):
- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_APP_URL`
- `OPENAI_API_KEY`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `STRIPE_PRICE_PRO_MONTHLY`
- `STRIPE_PRICE_PRO_YEARLY`
- `DATABASE_URL`

## License
MIT (c) 2026 Aurora Rayes LLC
