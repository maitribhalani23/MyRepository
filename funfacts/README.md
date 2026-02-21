# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default defineConfig([
  globalIgnores(['dist']),
  {
    # Fun Facts

    A small React + TypeScript + Vite project that displays fun facts. This repository contains the `funfacts` app and its development configuration.

    ## Overview

    This app demonstrates a minimal Vite + React + TypeScript setup with ESLint and basic project structure. It's intended as a starter for small React experiments.

    ## Installation

    Prerequisites: Node.js 18+ (or your preferred supported version) and npm or pnpm.

    1. Install dependencies:

    ```bash
    npm install
    # or
    pnpm install
    ```

    2. Install only the `funfacts` workspace (if using a monorepo tooling) — otherwise step 1 is sufficient.

    ## Usage

    Run the development server with hot-reload:

    ```bash
    npm run dev
    # or
    pnpm dev
    ```

    Build for production:

    ```bash
    npm run build
    # or
    pnpm build
    ```

    Preview the production build locally:

    ```bash
    npm run preview
    # or
    pnpm preview
    ```

    ## Where to look

    - Source code: `src/`
    - Config: `vite.config.ts`, `tsconfig.*.json`, `eslint.config.js`

    If you want a longer README (development setup, contributing, testing, license), tell me and I will expand this file.
