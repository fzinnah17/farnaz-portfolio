````md
# Farnaz Zinnah — Portfolio

[![CI](https://github.com/fzinnah17/farnaz-portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/fzinnah17/farnaz-portfolio/actions/workflows/ci.yml)

Personal engineering portfolio for Farnaz Zinnah, an AI Systems Engineer focused on AI systems, adversarial machine learning, systems performance, cloud AI, and AI governance.

## Stack

- Astro 7
- Tailwind CSS 4
- TypeScript 6
- Node.js 24
- Static output
- Astro-native client interactions
- GitHub Actions CI

## Design and interaction

The portfolio uses a restrained technical and editorial visual system rather than a conventional marketing-site layout.

Key interface features include:

- animated systems architecture in the hero
- structured system dossier identity block
- light and dark themes
- keyboard-accessible navigation
- Cmd/Ctrl + K command palette
- responsive social/contact rail
- filtered Selected Work gallery
- expandable project details
- accessible masonry project layout
- Experience and Stack registers
- horizontal Field Archive for professional events, hackathons, workshops, and communities
- Previous/Next, keyboard, trackpad, and swipe navigation in the archive
- reduced-motion support
- restrained one-time ceremonial transitions
- clean section navigation without URL fragments

## Accessibility

Accessibility is treated as a core part of the interface.

The site includes:

- keyboard navigation
- visible focus states
- skip navigation
- reduced-motion support
- screen-reader labels and semantic regions
- user-controlled archive navigation
- no autoplaying carousels
- no hover-only information
- responsive layouts for desktop and mobile
- accessible interactive target sizing

## Project structure

Components are grouped by responsibility:

```text
src/
├── assets/
│   └── portfolio/
│       └── archive/
│
├── components/
│   ├── archive/
│   ├── experience/
│   ├── hero/
│   ├── shell/
│   └── work/
│
├── layouts/
├── pages/
└── styles/
````

## Local development

Install dependencies:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

The development server normally runs at:

```text
http://localhost:4321
```

## Validation

Before committing or deploying, run:

```bash
npm run check
npm run build
```

## Continuous integration

GitHub Actions validates changes by running:

```bash
npm ci
npm run check
npm run build
```

## Deployment

The portfolio is generated as static output and can be deployed to Vercel.

Build command:

```text
npm run build
```

Output directory:

```text
dist
```

No environment variables are required for the current version.

## Professional links

The deployed portfolio includes links to:

* GitHub
* LinkedIn
* Resume
* selected public project repositories

````

Then save it and run:

```bash
npm run check
npm run build
````

