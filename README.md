# test-project

A Node.js web application built with **TypeScript** and **Next.js** (App Router).

## Tech Stack

| Category        | Technology              |
| --------------- | ----------------------- |
| Runtime         | Node.js                 |
| Language        | TypeScript              |
| Framework       | Next.js (App Router)    |
| Package manager | npm                     |
| Linting         | ESLint (Next.js default)|

## Prerequisites

- [Node.js](https://nodejs.org/) 18.18 or later (20+ recommended)
- npm (included with Node.js)

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd test-project
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables (optional)

Create a `.env.local` file in the project root and add any required variables for your environment.

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `npm run dev`   | Start the development server         |
| `npm run build` | Create a production build            |
| `npm run start` | Run the production server            |
| `npm run lint`  | Run ESLint                           |
| `npm test`      | Run tests (when configured)          |

## Project Structure

```
test-project/
├── app/               # Routes, layouts, and pages (App Router)
├── components/        # Reusable UI components
├── lib/               # Shared utilities and helpers
├── public/            # Static assets
├── cursor.md          # Cursor AI project guidance
├── next.config.ts     # Next.js configuration
├── tsconfig.json      # TypeScript configuration
└── package.json
```

## Development Notes

- Use TypeScript for all new source files.
- Follow existing patterns in the codebase before introducing new conventions.
- Keep changes focused and minimal.
- See [`cursor.md`](./cursor.md) for additional AI and project guidelines.

## License

ISC
