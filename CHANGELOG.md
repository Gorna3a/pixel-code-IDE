# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2026-10-03

### Changed
- Upgraded `next` and `eslint-config-next` from `15.5.9` to `16.1.1` (React 19.2.8 kept).
- Moved `app/favicon.ico` → `public/favicon.ico` and added `icons: { icon: "/favicon.ico" }` metadata in `app/layout.tsx` to fix `next build` (Turbopack) `PageNotFoundError: Cannot find module for page: /favicon.ico/route`.
- `README.md` stack updated to Next.js 16.1.1.

## [0.1.0] - 2026-10-03

### Added
- Initial plain Next.js 15.5.9 + TypeScript + App Router scaffold via `create-next-app` (plain CSS, no Tailwind, ESLint, npm, `@/*` import alias, no `src/` dir).
- Default starter files kept untouched: `app/layout.tsx`, `app/page.tsx`, `app/globals.css`, `app/page.module.css`, `public/`, `next.config.ts`, `tsconfig.json`.
- `README.md` rewritten for PixelCode IDE reboot (stack, getting started, structure, deferred roadmap).
- `CHANGELOG.md` created to track patches and changes going forward.

### Changed
- Downgraded scaffold default `next@16.3.8 / eslint-config-next@16.3.8` to `next@15.5.9 / eslint-config-next@15.5.9` to match requested Next 15 baseline.
- Renamed npm package `pixel-ide-scaffold` → `pixel-code-ide`.

### Removed
- Original placeholder `README.md` (`# pixel-code-IDE / ide for pixel code platform`).
- Scaffold `node_modules/` and `.next/` not committed (covered by `.gitignore`).
