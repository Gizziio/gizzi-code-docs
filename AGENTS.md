# gizzi-code-docs — Agent Guide

> Official documentation website for Gizzi Code.

## Quick Start

```bash
npm install
npm run dev
```

## Key Commands

| Command | What it does |
|---------|--------------|
| `npm run dev` | Start Vite dev server |
| `npm run build` | Production build to `dist/` |
| `npm run build:search` | Build + index with Pagefind |

## Directory Map

| Path | Purpose |
|------|---------|
| `src/pages/Home.tsx` | Landing / hero page |
| `src/components/Sidebar.tsx` | Navigation sidebar |
| `src/components/SearchModal.tsx` | In-app search |
| `dist/` | Production build output |

## Conventions

- **Stack:** Vite + React 18 + TypeScript + Tailwind CSS
- **Package manager:** npm
- **Theme:** Dark mode only, brand colors `#D4B08C` and `#D97757`

## Warnings

- Keep this site focused on Gizzi Code only. Platform docs belong in `allternit-docs`.
- The `dist/` folder is committed for easy static hosting; rebuild after content changes.

## Related Repos

- [`gizzi-code`](https://github.com/Gizziio/gizzi-code) — CLI source
- [`allternit-docs`](https://github.com/Gizziio/allternit-docs) — Platform documentation
