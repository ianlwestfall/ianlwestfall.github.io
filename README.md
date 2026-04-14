# ianlwestfall.github.io - Portfolio

[![CI](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/ci.yml/badge.svg)](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/ci.yml)
[![Deploy](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/deploy.yml)
[![Playwright](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/playwright.yml/badge.svg)](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/playwright.yml)

**Live site:** [ianlwestfall.github.io](https://ianlwestfall.github.io)

## Overview

A portfolio website built with React, TypeScript, and Vite as a modern maintainable portfolio project. It serves as a central place to present my work, background, and contact information in a polished, professional format. The project includes linting, formatting, unit testing, end-to-end testing, pre-commit checks, CI, and automated deployment.

## Features

- Responsive multi-page portfolio website
- Showcases projects, skills, education, and professional background
- Built with React, TypeScript, Vite, and Tailwind CSS
- Client-side routing with React Router
- Unit testing with Vitest
- End-to-end testing with Playwright
- Linting and formatting with ESLint and Prettier
- Pre-commit checks with Husky and lint-staged
- CI/CD and deployment with GitHub Actions and GitHub Pages

## Tech Stack

**Core:**

|                                              |                           |
| -------------------------------------------- | ------------------------- |
| [React](https://react.dev)                   | UI framework              |
| [TypeScript](https://www.typescriptlang.org) | Type-safe JavaScript      |
| [Vite](https://vite.dev)                     | Build tool and dev server |
| [Tailwind CSS](https://tailwindcss.com)      | Utility-first styling     |
| [React Router](https://reactrouter.com)      | Client-side routing       |

**Tooling:**

|                                                                                                       |                    |
| ----------------------------------------------------------------------------------------------------- | ------------------ |
| [ESLint](https://eslint.org)                                                                          | Linting            |
| [Prettier](https://prettier.io)                                                                       | Code formatting    |
| [Vitest](https://vitest.dev)                                                                          | Unit testing       |
| [Playwright](https://playwright.dev)                                                                  | End-to-end testing |
| [Husky](https://typicode.github.io/husky) + [lint-staged](https://github.com/lint-staged/lint-staged) | Pre-commit checks  |
| [GitHub Actions](https://github.com/features/actions)                                                 | CI/CD pipeline     |
| [GitHub Pages](https://pages.github.com)                                                              | Hosting            |

## Getting Started

Clone the repository, install dependencies, and start the development server:

```bash
git clone https://github.com/ianlwestfall/ianlwestfall.github.io.git
cd ianlwestfall.github.io
npm install
npm run dev
```

## Available Scripts

| Command                | Description                             |
| ---------------------- | --------------------------------------- |
| `npm run dev`          | Start the development server            |
| `npm run build`        | Build for production                    |
| `npm run preview`      | Preview the production build locally    |
| `npm run typecheck`    | Run TypeScript type checking            |
| `npm run lint`         | Run ESLint                              |
| `npm run lint:fix`     | Run ESLint with auto-fix                |
| `npm run format`       | Format the codebase with Prettier       |
| `npm run format:check` | Check formatting without changing files |
| `npm run test`         | Run unit tests in watch mode            |
| `npm run test:run`     | Run unit tests once                     |
| `npm run test:e2e`     | Run end-to-end tests                    |
| `npm run check`        | Run main local quality checks           |

## Deployment

This site is deployed with **GitHub Pages** using **GitHub Actions**.

Deployment runs automatically when changes are merged into `main`.
