# ianlwestfall.github.io - Portfolio

[![CI](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/ci.yml/badge.svg)](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/ci.yml)
[![Deploy](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/deploy.yml)
[![Playwright](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/playwright.yml/badge.svg)](https://github.com/ianlwestfall/ianlwestfall.github.io/actions/workflows/playwright.yml)

**Live site:** [ianlwestfall.github.io](https://ianlwestfall.github.io)

My professional portfolio site, built to showcase software development projects, education, career experience, technical skills and certifications, learning recommendations, hobbies, and more.

## Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Development Setup](#development-setup)
- [Scripts Reference](#scripts-reference)

## Overview

This site is built from scratch as a modern, maintainable portfolio using React, TypeScript, and Vite. It serves as a central place to present my work, background, and contact information in a polished, professional format.

This portfolio is intended to highlight:

- Software development projects
- IT and technical experience
- Education and certifications
- Technical skills and tools
- Contact and professional links
- Interesting hobbies

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
| [Husky](https://typicode.github.io/husky) + [lint-staged](https://github.com/lint-staged/lint-staged) | Pre-commit hooks   |
| [GitHub Actions](https://github.com/features/actions)                                                 | CI/CD pipeline     |
| [GitHub Pages](https://pages.github.com)                                                              | Hosting            |

## Development Setup

Clone the repo and install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

## Scripts Reference

| Command                | Description                             |
| ---------------------- | --------------------------------------- |
| `npm run dev`          | Start the development server            |
| `npm run build`        | Build for production                    |
| `npm run preview`      | Preview the production build locally    |
| `npm run lint`         | Run ESLint                              |
| `npm run format`       | Format the codebase with Prettier       |
| `npm run format:check` | Check formatting without changing files |
| `npm run test`         | Run unit tests in watch mode            |
| `npm run test:run`     | Run unit tests once                     |
| `npx playwright test`  | Run end-to-end tests                    |

## Deployment

This site is deployed with **GitHub Pages** using **GitHub Actions**.

Deployment runs automatically when changes are merged into `main`.

## Author

**Ian Westfall**
