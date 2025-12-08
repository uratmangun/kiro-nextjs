# Kiro Next.js Starter Template

A Next.js starter template with Kiro agent configuration, including pre-configured rules and workflows for AI-assisted development.

## Clone This Template

Use the GitHub CLI to create a new repository from this template:

```bash
gh repo create my-new-repo --template uratmangun/kiro-nextjs --public --clone
```

### Options

| Flag | Description |
|------|-------------|
| `--public` | Create a public repository |
| `--private` | Create a private repository |
| `--clone` | Clone the new repository locally |

### Prerequisites

- [GitHub CLI](https://cli.github.com/) installed and authenticated
- Run `gh auth login` if not already authenticated

## Getting Started

After cloning, install dependencies and start the development server:

```bash
bun install
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## What's Included

- **Next.js 15** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **Agent Configuration** (`.agent/`)
  - Pre-configured rules for development standards
  - Workflows for common tasks (auto-commit, README generation, etc.)
- **Kiro Hooks** (`.kiro/`) for automated agent behaviors

## Learn More

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Kiro Documentation](https://kiro.dev/docs) - learn about Kiro agent configuration
- [GitHub CLI](https://cli.github.com/manual/) - learn about GitHub CLI commands

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).
