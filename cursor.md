# Cursor Project Guide

This file provides context and instructions for Cursor AI when working in this project.

## Project Overview

- **Name:** test-project
- **Purpose:** Add a short description of what this project does.
- **Status:** Initial setup (Node.js + TypeScript + Next.js)

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Package manager:** npm
- **Styling:** (add when chosen — e.g. Tailwind CSS)
- **Linting:** ESLint (Next.js default)

## Project Structure

Standard Next.js layout:

```
test-project/
├── app/               # Routes, layouts, and pages (App Router)
├── components/        # Reusable UI components
├── lib/               # Shared utilities and helpers
├── public/            # Static assets
├── cursor.md          # AI guidance for this repo
├── next.config.ts     # Next.js configuration
├── tsconfig.json      # TypeScript configuration
└── package.json
```

## Development

### Setup

```bash
npm install
```

### Run

```bash
npm run dev      # Start dev server (http://localhost:3000)
npm run build    # Production build
npm run start    # Run production server
```

### Test

```bash
npm test         # Add when test runner is configured
npm run lint     # ESLint
```

## Coding Guidelines

- Keep changes focused and minimal.
- Follow existing patterns in the codebase.
- Prefer clear names over short or clever ones.
- Add comments only when the logic is not obvious.

## Notes for AI

- Read surrounding code before making changes.
- Do not commit unless explicitly asked.
- Ask before adding new dependencies or large refactors.
