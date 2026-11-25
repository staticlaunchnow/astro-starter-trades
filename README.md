# Northstar Plumbing & Mechanical — StaticLaunch Astro Starter (`astro-starter-trades`)

Free multi-page Astro starter template for plumbers, electricians, HVAC, and local contractors — deploy free on Cloudflare Pages.

## Deploy Free to Cloudflare Pages in 2 Minutes

1. Click **Use this template → Create a new repository** on GitHub (in *your* own GitHub account).
2. Edit **`src/data/site.ts`** with your real business name, phone, email, hours, and services (plus update `site` in `astro.config.mjs`).
3. In **Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git**, pick your new repository:
   - **Production branch:** `main`
   - **Framework preset:** `Astro`
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
   - **Environment variable:** `NODE_VERSION = 22.23.4`
4. Verify your live `*.pages.dev` URL, then attach your custom domain under **Custom domains**.

## Local Development

```bash
npm ci
npm run dev    # http://localhost:4321
npm run build  # Outputs static HTML to dist/
```

## Full Free Playbook & Guides
- **StaticLaunch Academy:** https://staticlaunch.com/academy/
- **Migration Playbooks (WordPress / Wix / Squarespace):** https://staticlaunch.com/migrate/
- **AI Prompt Library:** https://staticlaunch.com/prompts/
- **Optional Done-For-You Engineering:** https://fourak.com/ (Four Media Group LLC)
