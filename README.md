# Next.js + Tailwind CSS 4 Basic Setup

This is a minimal Next.js project with Tailwind CSS 4 configured.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Key Files

- `postcss.config.mjs` - PostCSS configuration with Tailwind 4 plugin
- `app/globals.css` - Global styles with `@import "tailwindcss"`
- `app/page.tsx` - Home page with Tailwind classes
- `app/layout.tsx` - Root layout component

## Tailwind CSS 4 Differences

- Uses `@tailwindcss/postcss` plugin instead of the old setup
- Uses `@import "tailwindcss"` in CSS instead of `@tailwind` directives
- No `tailwind.config.js` needed for basic usage (optional for customization)

