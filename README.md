# SETUP - REACT - TS - ESLINT - PRETTIER - HUSKY

## Installation

1. Clone repository

```bash
git clone https://github.com/Fahrulmosaja/Planto.git
```

2. Install dependencies

```bash
npm install
```

5. Run application

```bash
npm run dev
```

## Setup

1. ESLint

```bash
npm install prettier --save-dev eslint-config-prettier eslint-plugin-prettier
```

```bash
npm run lint
```

2. Husky

```bash
npm install --save-dev husky lint-staged
```

This command creates a .husky folder with pre-commit file. In this file you can add commands to run each time we add a commit. By default the file contains only npm test command. Replace it with:

```bash
npx husky init
```

```bash
npx lint-staged
```

3. Run

```bash
npm run prepare
```

```bash
git add .
git commit -m "test the setup"
```
