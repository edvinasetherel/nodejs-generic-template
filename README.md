# Node.js Generic Template

A template repository for Node.js projects with TypeScript, Vite, ESLint, Vitest, and Husky pre-configured.

## Features

- TypeScript with ES2024 target
- Vite for fast development and building
- ESLint with stylistic rules
- Vitest for unit and acceptance testing
- Husky git hooks (lint + unit tests on commit, full tests on push)

## Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm lint` - Run ESLint
- `pnpm lint:fix` - Run ESLint with auto-fix
- `pnpm test` - Run all tests
- `pnpm test:unit` - Run unit tests only
- `pnpm test:acceptance` - Run acceptance tests only

## Project Structure

```
tests/
  unit/           # Unit tests
  acceptance/     # Acceptance tests
src/              # Source code
```
