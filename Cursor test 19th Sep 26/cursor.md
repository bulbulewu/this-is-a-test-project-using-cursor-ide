# Cursor

Project notes and guidance for this folder.

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)

## Overview

This is a Node.js project built with TypeScript and Next.js. Use this file to give Cursor context when working in this directory.

## Conventions

- Use TypeScript for all application code; avoid `any` unless unavoidable.
- Follow Next.js App Router patterns (`app/` directory, Server Components by default).
- Prefer Server Components; use Client Components (`"use client"`) only when needed (interactivity, hooks, browser APIs).
- Colocate route-specific logic under `app/`; shared utilities in `lib/` or `utils/`.
- Use `async`/`await` for async work; handle errors explicitly.
- Keep changes focused and minimal — only modify what the task requires.

## Suggested Structure

```
app/           # Routes, layouts, pages (App Router)
components/    # Reusable UI components
lib/           # Shared helpers, API clients, config
types/         # Shared TypeScript types
public/        # Static assets
```

## Commands

- `npm run dev` — start development server
- `npm run build` — production build
- `npm run lint` — run ESLint
