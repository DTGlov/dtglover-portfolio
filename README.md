# David Tawiah Glover — Portfolio

A calm, responsive portfolio built with Astro, TypeScript, and custom CSS.

## Development

Requires Node.js 22.12+ and npm 9.6.5+. The initial build used the already-installed Node at `/opt/homebrew/bin/node`; the machine's default shell currently selects Node 16. Select a supported installed Node version before running npm.

```sh
npm ci
npm run dev
npm run check
npm run build
npm run preview
npm run format:astro
npm run format:astro:check
```

The repository configures Prettier for `.astro` files. With the Astro and Prettier editor extensions installed, saving an Astro file formats it automatically. `npm run format:astro` formats the existing Astro files from the terminal.

## Structure

- `src/pages/index.astro`: homepage
- `src/pages/work/`: Hubtel and Sika case studies
- `src/components/`: navigation, footer, shared icons
- `src/styles/global.css`: shared tokens and responsive styles
- `src/assets/projects/`: project screenshots supplied by David
- `public/images/`: symbolic pixel character

The Hubtel and Sika case studies include screenshots in scrollable, responsive galleries. Current work covers remain typography-led editorial compositions. Hubtel screenshots containing personal information were excluded. No private source code or credentials from Hubtel or Sika are included.

Contact uses a mailto link. No database, contact-form service, analytics, or external font requests. Social links open normally. A custom domain and canonical URL can be configured when hosting is selected.

GitHub Actions checks types and builds on pull requests and main pushes. Hosting is intentionally deferred. Review and merge changes through pull requests.
