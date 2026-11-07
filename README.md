# Astro Shadcn UI Template

A starter template for Astro 7 with shadcn/ui, React 19, and Tailwind CSS 4.

## Getting Started

Requires Node.js (see `.nvmrc`) and pnpm.

```bash
git clone --depth=1 https://github.com/peeranat-dan/astro-shadcn-ui-template
cd astro-shadcn-ui-template
pnpm install
pnpm dev
```

## Features

- Astro 7 with React islands
- Tailwind CSS 4 via `@tailwindcss/vite`
- shadcn/ui components built on `radix-ui`
- Dark mode toggle with persisted preference

## Adding Components

```bash
pnpm dlx shadcn@latest add <component>
```

## Scripts

| Command        | Description              |
| -------------- | ------------------------ |
| `pnpm dev`     | Start dev server         |
| `pnpm build`   | Build for production     |
| `pnpm preview` | Preview production build |
