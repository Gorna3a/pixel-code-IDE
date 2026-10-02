# PixelCode IDE

Fresh reboot of the PixelCode IDE — a beginner-focused, browser-based coding platform.

This repo currently holds a **plain Next.js + TypeScript starting point**. No IDE features,
theming, execution backends, or AI tutor code yet — those will be added incrementally
following a YouTube tutorial.

Context from the original platform (for later work): courses/lessons, challenges, arena,
playground (Judge0, 14 languages), multi-file studio workspace, Gemini AI chat, i18n + RTL,
admin panel, and retro neobrutalism themes ("Beige Computer" / "Phosphor Night").

## Stack

- Next.js 16.1.1 + App Router
- TypeScript
- ESLint (`eslint-config-next`)
- Plain CSS (CSS vars + CSS Modules — no Tailwind)
- npm

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser.

Edit `app/page.tsx` — the page auto-updates as you edit.

## Scripts

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start dev server         |
| `npm run build` | Production build         |
| `npm run start` | Start production server  |
| `npm run lint`  | Run ESLint               |

## Project Structure

```text
app/
  layout.tsx      # root layout
  page.tsx        # homepage (default Next.js starter)
  globals.css     # global styles
  page.module.css # homepage styles
public/           # static assets (favicon.ico, next.svg, vercel.svg, …)
next.config.ts
tsconfig.json
eslint.config.mjs
```

## Roadmap (deferred)

- Retro neobrutalism theme tokens (`:root` CSS vars, light/dark + Kids themes)
- IDE shell: file explorer, editor tabs, preview/terminal panels
- Code execution (Judge0 and/or in-browser runtimes)
- Persistence (cloud / localStorage), GitHub + folder import
- AI tutor chat, courses, challenges, arena — only if/when requested

## Version log

See [CHANGELOG.md](./CHANGELOG.md) for patch-by-patch notes (Keep a Changelog format).

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)
