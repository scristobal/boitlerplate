# Boitlerplate

A full-on batteries included template to get you started.

## Devdepencencies

wThis boiler plate includes:

-   TypeScript (static analysis)
-   Vite (build system)
-   Vitest (test framework)
-   Eslint (rule based linter)
-   Prettier (formatter)
-   Husky (pre-commit manager)
-   Nvm (node version manager)
-   GitHub actions (continuos integration and delivery)
-   Other utility functions (npm-run-all, nvm-auto, npm-check-updates, webhints, ts-fix)

## NPM Scripts

In addition to standard Vite commands like `npm run build` and `npm run preview`

-   `npm run dev` launch the development server and test runner\*
-   `npm run check` check for types, lint, formatting and test problems
-   `npm run fix` run lint, types and format auto-fixers
-   `npm run update` launch the interactive CLI to update dependencies

The original Vite dev server can be launched with `npm run dev:server`

## GitHub Pages

In order to configure github pages:

1. Go to the repo `Settings` > `Pages` > `Build and deployment` and choose `GitHub Actions` from the drop down menu.

2. Either setup a [custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) or change the [vite config](./vite.config.js) to [specify a base URL](https://vitejs.dev/config/shared-options.html#base)
