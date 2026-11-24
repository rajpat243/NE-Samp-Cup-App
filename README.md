# NE Samp Cup App

Web app for the NE Samp Cup regional basketball tournament. Next.js (App Router), TypeScript, Tailwind. Deployed on Vercel.

## Local dev

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Workflow

1. Branch off `main` (`git checkout -b feature/whatever`). Push to your branch as often as you like; no approval needed.
2. Every push to a branch gets a Vercel preview URL (posted on the PR).
3. Open a PR into `main`. It needs **1 approval** and a passing **CI** check (lint, typecheck, build) before it can merge.
4. Merging to `main` deploys to production on Vercel automatically.

Direct pushes and force pushes to `main` are blocked.
