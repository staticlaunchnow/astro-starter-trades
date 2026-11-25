# Website Development Instructions (astro-starter-trades)

This website uses the StaticLaunch static-first standard (Astro + GitHub + Cloudflare Pages).

## Rules for AI & Human Contributors
1. Read README.md and src/data/site.ts first — update centralized business info in src/data/site.ts whenever possible.
2. Keep reusable CSS variables in src/styles/global.css; avoid scattered inline styles.
3. Maintain semantic HTML (one <h1> per page, header/nav/main/footer landmarks) and WCAG 2.2 AA contrast.
4. Keep SEO metadata, canonical URLs, JSON-LD, robots.txt, and sitemap.xml up to date.
5. Never commit secrets, passwords, or .env files.
6. Run `npm run build` and review diffs before pushing to `main`.
