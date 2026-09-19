# Pasanaku docs

User and implementation docs for Pasanaku — onchain rotating savings pools
backed by ERC-4626 vault shares.

Canonical contract behavior lives in
[core-v2](https://github.com/PasanakuOnchain/core-v2). These pages explain that
behavior for participants and integrators.

## Setup

```bash
npm install
npm run docs:dev
```

Requires Node.js 20+.

## Scripts

| Command                             | Description              |
| ----------------------------------- | ------------------------ |
| `npm run docs:dev`                  | VitePress local server   |
| `npm run docs:build`                | Production build         |
| `npm run docs:preview`              | Preview production build |
| `npm run format` / `npm run format:check` | Oxfmt              |
