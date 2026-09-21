# Mahmoud Badi — Portfolio

Responsive static portfolio with dark/light themes, Lucide icons, project galleries, a Barakah video demo, and an interactive terminal.

## Deploy on Vercel

Import this GitHub repository in Vercel. Use the repository root as the Root Directory. The included `vercel.json` selects the Other framework preset, skips the build step, and serves `dist/`.

After deployment, add `mahmoudbadi.com` in the project's Domains settings and apply the DNS records Vercel provides in Cloudflare.

## Local preview

Run `python3 -m http.server 4173 --directory dist` and open http://localhost:4173.

## Files

- `dist/index.html`: content and markup
- `dist/style.css`: styling and responsive layout
- `dist/app.js`: themes, dialogs, terminal, and pointer interactions
- `dist/assets/`: supplied images, compressed demo video, résumé, and icon license

All résumé links use `/assets/Mahmoud-Badi-Resume.pdf` relative to the deployed document and open the supplied PDF directly. Update that file to replace the résumé.

Company logos reference external image hosts. WebRise remains a text wordmark. Lucide SVG icons are embedded locally, with their license in `dist/assets/LUCIDE-LICENSE`.
