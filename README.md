# Zelalem B. Bogale portfolio

A responsive personal portfolio built with Next.js App Router, TypeScript, and Tailwind CSS. Features dark/light themes, accessible project filters, six case-study routes, inline animated SVG, metadata, sitemap, and Open Graph image.

## Local development

Requires Node.js 20 or newer.

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Production checks

```bash
npm run lint
npm run build
```

## Editing content

Edit `content/site.ts` for biography, experience, skills, certifications, contact details, and the production URL. Edit `content/projects.ts` to add, remove, or update projects. Each project requires a unique `slug`; the case-study page is generated automatically at `/projects/<slug>`.

The six included projects are illustrative. Their performance claims and repository URLs must be replaced with verifiable work before representing them as completed projects.

The CV is a dedicated responsive page at `/cv`, with a print-friendly layout. Use the browser Print command and select Save as PDF if a downloadable document is needed. The headshot lives at `public/zelalem-headshot.webp`.

Set `site.url` to your deployed domain so canonical metadata and the sitemap use the correct host.

## Deployment

Import this repository into Vercel, choose the Next.js framework preset, and deploy. Commits to the production branch trigger automatic redeployments.

## Accessibility

Keyboard-friendly navigation, semantic headings, labeled controls, and reduced-motion support are included. Test with assistive technology before production launch.
