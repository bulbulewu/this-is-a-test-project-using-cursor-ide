# test-project

A test project for exploring Cursor IDE workflows and Node.js tooling.

## Description

This is a Node.js project used to experiment with Cursor IDE, project rules, and environment configuration. See `cursor.md` for planned conventions and future stack direction.

## Tech Stack

**Current**

- Node.js (>= 12)
- npm
- [dotenv](https://www.npmjs.com/package/dotenv) — load environment variables from `.env`

**Planned** (see `cursor.md`)

- TypeScript
- Next.js (App Router)

## Project Structure

```
.
├── .cursor/
│   └── rules/          # Cursor IDE project rules
├── cursor.md           # Project notes and Cursor guidance
├── package.json
├── package-lock.json
└── README.md
```

## Prerequisites

- [Node.js](https://nodejs.org/) v12 or later
- npm

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create a `.env` file in the project root (optional):

   ```env
   # Example
   # API_KEY=your-key-here
   ```

3. Load environment variables in your entry file:

   ```js
   require('dotenv').config();
   ```

4. Run the app (once `index.js` exists):

   ```bash
   node index.js
   ```

## Scripts

| Command    | Description                          |
|------------|--------------------------------------|
| `npm test` | Placeholder — no tests configured yet |

## Development Guidelines

- Keep changes focused and minimal
- Match existing naming, structure, and conventions
- Prefer clear, self-documenting code
- Ask before large architectural changes or new dependencies

These are also defined in `.cursor/rules/project.mdc`.

## License

Not specified.
