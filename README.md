# Charity Minds 2

Simple multi-page frontend project for a charity platform interface.

## Live Demo

- Vercel: [https://charity-minds-2.vercel.app](https://charity-minds-2.vercel.app)

## Pages

- `public/index.html` - Home page
- `public/login.html` - Login page
- `public/Register.html` - Registration page
- `public/dashboard.html` - Dashboard with stats and users table

## Tech Stack

- HTML
- Tailwind CSS v4 (via `@tailwindcss/cli`)
- Plain JavaScript (`public/about.js`)

## Project Structure

```text
charity-minds-2/
├─ public/
│  ├─ assets/
│  │  ├─ css/style.css
│  │  └─ images/logo.png
│  ├─ index.html
│  ├─ login.html
│  ├─ Register.html
│  ├─ dashboard.html
│  └─ about.js
├─ src/
│  └─ input.css
├─ package.json
└─ README.md
```

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Start Tailwind in watch mode:

```bash
npm run dev
```

3. Open any page in the browser from the `public` folder, for example:

- `public/index.html`
- `public/dashboard.html`

## Build Notes

- Tailwind input file: `src/input.css`
- Tailwind output file: `public/assets/css/style.css`
- If you change classes in HTML, keep `npm run dev` running so CSS updates automatically.

## Current Improvements

- Dashboard navigation is cleaned up and aligned.
- Welcome message is properly positioned in a dedicated card.
- Registered users table has professional spacing, striping, and hover states.
- Registration form supports responsive split fields.

## Author

Brian
