# Heaven's Classics

> One-line summary of what the project does and who it serves.

## Document Metadata

| Field | Value |
| --- | --- |
| Project | `Heaven's Classics` |
| Status | `ACTIVE` |
| Owner | `Ranit Saha (Coderooz)` |
| Primary Language(s) | `TypeScript, JavaScript` |
| Repository | `https://github.com/coderooz/heavens-classics` |
| Documentation Version | `0.1.0` |
| Last Updated | `2026-04-23` |

## At A Glance

- Problem solved: `{{PROBLEM_STATEMENT}}`
- Target users: `{{USERS_OR_TEAMS}}`
- Supported environments: `{{LOCAL | CLOUD | MOBILE | SERVER | CLI}}`
- Main entry points: `{{ENTRY_POINTS}}`

## External Links

- Repository: `https://github.com/coderooz/heavens-classics`
- Live application: `{{PRODUCTION_URL}}`
- Staging environment: `{{STAGING_URL}}`
- API reference: `{{API_DOCS_URL}}`
- Package registry: `{{PACKAGE_URL}}`
- Design files: `{{DESIGN_URL}}`
- Issue tracker: `https://github.com/coderooz/heavens-classics/issues`
- Discussions: `https://github.com/coderooz/heavens-classics/discussions`
- Changelog: `https://github.com/coderooz/heavens-classics/blob/main/CHANGELOG.md`
- Security policy: `https://github.com/coderooz/heavens-classics/blob/main/SECURITY.md`

## Table Of Contents

1. Overview
2. Goals
3. Repository Structure
4. Tech Stack
5. Getting Started
6. Configuration
7. Common Workflows
8. Usage Examples
9. Architecture Notes
10. Testing Strategy
11. Deployment
12. Troubleshooting
13. Contributing
14. Roadmap
15. FAQ

## Overview

Describe the project in one or two short paragraphs.

Cover:

- What the project is
- Why it exists
- What is included in this repository
- What is intentionally out of scope

## Goals

- `{{PRIMARY_GOAL_1}}`
- `{{PRIMARY_GOAL_2}}`
- `{{PRIMARY_GOAL_3}}`

## Repository Structure

```text
heavens-classics/
|-- app/
|   |-- layout.tsx
|   |-- page.tsx
|   `-- globals.css
|-- public/
|-- demo/
|-- .github/
|-- .next/
|-- node_modules/
|-- package.json
|-- tsconfig.json
|-- next.config.ts
|-- postcss.config.mjs
|-- eslint.config.mjs
`-- .gitignore
```

Add a short explanation for the most important directories:

- `app/`: Next.js App Router pages and layout components
- `public/`: Static assets served directly
- `demo/`: Demo content and examples
- `.github/`: GitHub workflows and issue templates

## Tech Stack

| Area | Choice | Notes |
| --- | --- | --- |
| Language(s) | TypeScript, JavaScript | Strict TypeScript enabled |
| Framework | Next.js 16 | React 19 with App Router |
| Styling | Tailwind CSS v4 | PostCSS integration |
| Package Manager | npm | Node.js 20+ |
| Runtime | Node.js | Server-side rendering support |
| Hosting | Vercel | Optimized for Vercel deployment |
| Linting | ESLint 9 | Next.js and TypeScript configs |

## Getting Started

### Prerequisites

- Node.js 20 or higher
- npm 10+ (or yarn, pnpm, bun)

### Installation

```bash
# Clone the repository
git clone https://github.com/coderooz/heavens-classics.git

# Navigate to project directory
cd heavens-classics

# Install dependencies
npm install
```

### First Run

```bash
# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Configuration

### Environment Variables

| Variable | Required | Default | Description |
| --- | --- | --- | --- |
| `{{ENV_VAR_1}}` | `yes` | `{{DEFAULT}}` | `{{DESCRIPTION}}` |
| `{{ENV_VAR_2}}` | `no` | `{{DEFAULT}}` | `{{DESCRIPTION}}` |

### Project Configuration

| File | Purpose |
| --- | --- |
| `tsconfig.json` | TypeScript compiler options |
| `next.config.ts` | Next.js configuration |
| `postcss.config.mjs` | PostCSS and Tailwind CSS configuration |
| `eslint.config.mjs` | ESLint linting rules |

## Common Workflows

| Goal | Example Command | Notes |
| --- | --- | --- |
| Start development server | `npm run dev` | Hot-reload enabled |
| Build for production | `npm run build` | Creates optimized build |
| Start production server | `npm start` | Serves production build |
| Run linter | `npm run lint` | ESLint checks |
| Format code | `npx prettier --write .` | Prettier formatting |

## Usage Examples

### Example 1

```tsx
// Your example code here
```

## Architecture Notes

Summarize the system in plain language before going deep.

### Key Components

- `{{COMPONENT_1}}`: `{{RESPONSIBILITY}}`
- `{{COMPONENT_2}}`: `{{RESPONSIBILITY}}`
- `{{COMPONENT_3}}`: `{{RESPONSIBILITY}}`

### Data Flow

```text
{{INPUT}} -> {{PROCESSING}} -> {{OUTPUT}}
```

### Important Decisions

- `{{DECISION_1}}`
- `{{DECISION_2}}`

## Testing Strategy

- Unit tests: `{{UNIT_TEST_APPROACH}}`
- Integration tests: `{{INTEGRATION_TEST_APPROACH}}`
- End-to-end tests: `{{E2E_TEST_APPROACH}}`

If there are gaps, state them clearly.

## Deployment

### Environments

| Environment | URL | Purpose |
| --- | --- | --- |
| Local | `http://localhost:3000` | Development |
| Staging | `{{STAGING_URL}}` | `{{PURPOSE}}` |
| Production | `{{PRODUCTION_URL}}` | `{{PURPOSE}}` |

### Release Process

1. `{{RELEASE_STEP_1}}`
2. `{{RELEASE_STEP_2}}`
3. `{{RELEASE_STEP_3}}`

## Troubleshooting

### Common Problems

| Problem | Likely Cause | Fix |
| --- | --- | --- |
| `{{PROBLEM_1}}` | `{{CAUSE_1}}` | `{{FIX_1}}` |
| `{{PROBLEM_2}}` | `{{CAUSE_2}}` | `{{FIX_2}}` |

## Contributing

- Point contributors to `README.md`, this document, and any contribution rules.
- Explain branch naming, review expectations, and local validation steps.
- Link related GitHub templates or project standards.
- Follow the [CONTRIBUTING.md](./CONTRIBUTING.md) guidelines.

## Roadmap

- `{{ROADMAP_ITEM_1}}`
- `{{ROADMAP_ITEM_2}}`
- `{{ROADMAP_ITEM_3}}`

## FAQ

### What is this project about?

`{{ANSWER_1}}`

### How do I deploy this project?

The project is optimized for Vercel deployment. Run `vercel` in the project root or connect your GitHub repository to Vercel.

### Can I use this with other frameworks?

This template is built specifically for Next.js. For other frameworks, consider the [Coderooz Docs Template](https://github.com/coderooz/Docs-Template).