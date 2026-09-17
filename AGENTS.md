# Portfolio engineering

- Astro static site with TypeScript and custom CSS. No backend or database.
- Shared document layout in src/layouts, reusable UI in src/components, routes in src/pages, design tokens in src/styles/global.css.
- Keep content accurate: Hubtel is professional team work; David owns the Pay Small Small mobile implementation. Sika web is live and iOS is in development.
- Sika timeline: initially built with Claude, paused, then revived with ChatGPT. Do not imply it was inherited from another engineer.
- Do not invent metrics, testimonials, screenshots, or production status.
- No personal photograph. Use the symbolic pixel avatar.
- Project screenshots belong in src/assets/projects/{hubtel,sika}. Import through Astro image tooling, include dimensions and descriptive alt text, and remove private data before adding assets.
- Motion must respect prefers-reduced-motion. All controls must work with keyboard and touch.
- Keep main body text at least 16px. Verify mobile at 375px, desktop, and keyboard navigation.
- No animation libraries until a concrete need warrants one.
- Run npm run check and npm run build. Review git diff/status before handoff.
- Work on feature branches. User reviews and merges to main. No deployment until explicitly requested.
- Never edit the user's Hubtel or Sika source repositories as part of this project.
