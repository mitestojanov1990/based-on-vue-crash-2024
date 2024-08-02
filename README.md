# Vue Jobs Project (YouTube)

Forked from [*bradtraversy* (https://github.com/bradtraversy/vue-crash-2024)]

## Usage

This project uses JSON-Server for a mock backend.

**vite.config.js**: Vite configuration for setting up plugins, server settings, and path aliases.

**vitest.config.js**: Configuration for Vitest, extending Vite's config for testing.

**tsconfig.json**: Base TypeScript configuration with references to sub-configs.

**tsconfig.app.json**: TypeScript configuration for the application code.

**tsconfig.node.json**: TypeScript configuration for Node.js-specific files.

**tsconfig.vitest.json**: TypeScript configuration for Vitest.

**tailwind.config.js**: Tailwind CSS configuration for theme customization and utility classes.

**postcss.config.js**: Configuration for PostCSS with Tailwind CSS and autoprefixer plugins.

**playwright.config.ts**: Playwright configuration for end-to-end testing.

**env.d.ts**: TypeScript environment declaration file.

**.prettierrc.json: Prettier configuration for code formatting.**

**.eslintrc.cjs: ESLint configuration for linting JavaScript and TypeScript files.**

### Install Dependencies

```bash
npm install
```

### Run JSON Server

The server will run on http://localhost:8000

```bash
npm run server
```

### Run Vite Frontend

Vue will run on http://localhost:3000

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```
