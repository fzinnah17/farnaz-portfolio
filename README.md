# Farnaz Zinnah — Portfolio

[![CI](https://github.com/fzinnah17/farnaz-portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/fzinnah17/farnaz-portfolio/actions/workflows/ci.yml)

Personal engineering portfolio for Farnaz Zinnah, an AI Systems Engineer working across AI infrastructure, distributed systems, adversarial machine learning, and AI governance.

## Stack

- Astro 7
- Tailwind CSS 4
- TypeScript 6
- Node.js 24
- Static output
- Astro-native client interactions
- GitHub Actions CI

## Interface

The portfolio uses an engineering-inspired design language rather than a conventional marketing-site layout.

Features include:

- ambient distributed-systems network visualization
- structured JSON identity block
- one-time typing sequence
- experience rendered as a development log
- stack rendered as a dependency manifest
- expandable project details
- Cmd/Ctrl + K command palette
- persistent scroll progress
- light and dark themes
- reduced-motion support
- keyboard skip navigation
- responsive contact rail

## Local development

Install dependencies:

```bash
npm install
```

Run locally:

```bash
npm run dev
```

The development server normally runs at:

```text
http://localhost:4321
```

## Validation

Run:

```bash
npm run check
npm run build
```

## Resume

The site automatically exposes the Resume link once the file exists.

## Deployment

The site is built as static output and can be deployed to Vercel.

Build command:

```text
npm run build
```

Output directory:

```text
dist
```

No environment variables are required for v1.

## CI

GitHub Actions validates every pull request by running:

```bash
npm ci
npm run check
npm run build
```