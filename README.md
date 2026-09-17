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
```

## Structure

- `src/pages/index.astro`: homepage
- `src/pages/work/`: Hubtel and Sika case studies
- `src/components/`: navigation, footer, shared icons
- `src/styles/global.css`: shared tokens and responsive styles
- `src/assets/projects/`: project screenshots supplied by David
- `public/images/`: symbolic pixel character

Screenshots have not been supplied yet. Current work covers are typography-led editorial compositions, not representations of either app's interface. See each asset folder's README for the requested images. No private source code or credentials from Hubtel or Sika are included.

Contact uses a mailto link. No database, contact-form service, analytics, or external font requests. Social links open normally. A custom domain and canonical URL can be configured when hosting is selected.

GitHub Actions checks types and builds on pull requests and main pushes. Hosting is intentionally deferred. Work is on `feat/portfolio`; review and merge through a pull request.
