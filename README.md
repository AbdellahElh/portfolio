# Abdellah El Halimi | Portfolio (Astro + Tailwind)

Fast, type-safe portfolio that **pulls your projects from GitHub at build-time**, merges `Appointment-app-front` and `Appointment-app-back` into a single project card, and **excludes** `project`, `pwd-manager-backend`, and `pwd-manager-frontend` (because the monorepo `pwd-manager` already covers them).

## Quick start

```bash
# 1) Install deps
npm i

# 2) Start dev server
npm run dev
# open http://localhost:4321

# 3) Build
npm run build && npm run preview
```

### Customize

- Edit contact info in `src/components/Header.astro` and the `#contact` section in `src/pages/index.astro`.
- Update the featured list in `src/pages/index.astro` to pin repos.
- GA4 certificate PDF lives at `public/certificates/ga4.pdf` with a public link on the page.

### Deploy

Deploy to Vercel/Netlify. No secrets required. The site calls the public GitHub API at build time.
