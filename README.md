# Next.js + ESLint + Prettier Boilerplate

This is a template for starting a new Next.js v12 project. It's comes pre-configured with both ESLint and Prettier.
Formatting and syntax rules are enforced on both save & pre-commit. To see a detailed breakdown of the formatting rules used, click [here](.eslintrc.json).

# Setup

Follow the steps below to use this template.

## 1. Run `create-next-app`

```shell
npx create-next-app your-app-name --example https://github.com/pvmathew/next12-ts-prettify
```

## 2. Install the required extensions

Open your project in Visual Studio Code and install the required extensions: `Prettier` & `ESLint`
These extensions are used in order to auto-fix formatting & syntax errors when saving.

## 3. Start the development server

```shell
npm run install
npm run dev
```

# Directory Structure

All of the project files can be found within `/src`.
Any custom types & interfaces are to be placed within the `types` folder.

```js
.
├── .next
├── public // Images, Fonts, and other assets
├── src
│   ├── components
│   │   ├── login // Login page components
│   │   ├── common // Common components
│   ├── hooks // Custom hooks
│   ├── types // Custom types/interfaces
│   ├── utils // Utility functions
│   ├── pages // Page components
│   │   ├── _app.tsx
│   │   ├── _document.tsx
│   │   ├── login.tsx
│   │   └── index.tsx
│   └── styles // Global styles
...
```
