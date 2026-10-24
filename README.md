# Awesome-Portfolio-Website-Builder

# Top Portfolio Website Builder Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Self-Hosted Portfolio Builders, Static Site Generators & Ownership-First Publishing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Portfolio Website Builders**. These tools help designers, photographers, developers, and creators showcase their work online — with a spectrum running from polished subscription services to open-source builders where you own the code, the data, and the permanence of your portfolio.

**Examples** include Open Bento, Silex, Microfolio, CodeFX, and Astro Portfolio Templates (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, static deployment, and transparent data ownership — especially relevant as **Bento.me shut down**, leaving creators looking for portfolio tools that can never be discontinued by a company decision [citation:1].

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Adobe Portfolio** — Adobe's portfolio website builder bundled with Creative Cloud subscriptions. Integrates with Behance and Adobe Fonts, with responsive templates and custom domains. **Best for Adobe subscribers** wanting a simple portfolio without a separate hosting bill, accepting Creative Cloud dependency.

- **Squarespace** — Design-forward website builder with polished templates and built-in e-commerce. **Subscription-based** from around $16/month. **Best for creatives** wanting beautiful templates and zero technical setup, accepting monthly fees and platform lock-in.

- **Cargo Collective** — Portfolio platform popular among designers and artists. **Subscription-based** with custom domains and community features. **Best for designers** wanting a curated, design-community-oriented portfolio host.

- **Format** — Portfolio builder for photographers and visual artists. **Subscription-based** with client proofing and e-commerce features. **Best for photographers** wanting portfolio plus client delivery in one platform.

## Open-Source GitHub Projects

- **Open Bento (open-bento-me)** — **The open-source revival of Bento.me for GitHub Pages.** MIT licensed, created after Bento.me shut down to ensure portfolios can outlive companies [citation:1]. **Deploy in 5 minutes to GitHub Pages or self-host** — your data never touches a server, going directly from your browser to your GitHub repo via the GitHub API [citation:1]. **Card-based portfolio builder** with Link cards (auto-fetches title and image), GitHub Repo cards (stars, language, description), HuggingFace cards (models, datasets), Image, Text, Section Title, and NeedBoard cards for collaboration [citation:1]. **Tech stack**: Next.js 15 with static export, Tailwind CSS + Radix UI, react-grid-layout for drag-and-drop, and GitHub Pages for free hosting [citation:1]. **Security-conscious**: GitHub token stored base64-encoded in browser localStorage, sent directly to GitHub API, only repo scope needed, revocable anytime [citation:1]. **Best for creators** wanting a beautiful link-in-bio style portfolio they fully own, with zero hosting cost and no company that can shut it down [citation:1].

- **Silex** — **The free/libre no-code website builder for the static web.** AGPL-3.0 licensed, **1,844 GitHub stars**, actively developed for almost 8 years with 31 contributors [citation:14]. **Drag-and-drop visual builder** generating clean static HTML — described as "next gen Webflow for the static web" [citation:14]. **Self-hosted or desktop app**, with white-label options for agencies. **Best for designers** wanting Webflow-style visual building without subscription fees or proprietary runtime, accepting the AGPL license and self-hosting setup.

- **Microfolio** — **The modern static portfolio generator built on SvelteKit 2 and Tailwind CSS 4.** **Privacy by construction**: no cookies, no analytics, no tracking scripts, no consent banner required — the only thing stored is the visitor's light/dark theme preference [citation:8]. **Performance-focused**: every page prerendered, content in HTML for SEO and no-JS readability, WebP thumbnails and sharing images generated at build [citation:8]. **Features**: image optimization, shareable URLs with filter/search/sort state, internationalization (English/French, RTL-ready), Open Graph and Twitter tags, sitemap.xml, robots.txt, pagination, and a map with no API key using OpenFreeMap [citation:8]. **Install via Homebrew** (`brew install aker-dev/tap/microfolio`) or manual Node.js setup [citation:8]. **Best for photographers and visual creators** wanting a fast, privacy-first portfolio with excellent performance and no tracking [citation:8].

- **CodeFX** — **The modular multi-platform portfolio framework.** MIT licensed, **one codebase deploys to GitHub Pages (static), Vercel (serverless), self-hosted (full-stack), or shared hosting (FTP)** [citation:12]. **Modular architecture**: enable only what you need — portfolio, theme, social, auth (invisible login via secret keyboard shortcut), CMS (click-to-edit inline), email, ticket, forum, analytics [citation:12]. **Database abstraction**: flatfile (no dependencies), SQLite, PostgreSQL, or MySQL [citation:12]. **Theme engine** with 5 presets, custom colors, and dark mode [citation:12]. **Best for developers** wanting a portfolio that can grow into a community platform, with deployment flexibility across static and full-stack targets [citation:12].

- **Astro Design/Photography Portfolio** — **The free Astro template for designers and photographers.** Built with Astro, with light/dark mode, responsive mobile layout, and bilingual documentation (English and Chinese) [citation:2]. **Live demo available**, with a submission list for sites built with the template [citation:2]. **Best for designers and photographers** wanting a lightweight, modern static portfolio with Astro's performance benefits and minimal setup [citation:2].

- **Horizon (Cosmic Themes)** — **The free photography website template for Astro.** GPL-3.0 licensed, built with Astro and Tailwind CSS . **Quickstart**: fork, `npm install`, `npm run dev`, customize site URL in `astro.config.mjs`, deploy to Netlify, Vercel, Cloudflare, or any provider . **Best for photographers** wanting a free, well-structured Astro photography theme with straightforward deployment .

- **Foil** — **The portfolio CMS library for engineers and technical artists.** Built on **Rust, Node.js, TypeScript, React, GraphQL, and PostgreSQL** [citation:3]. **Designed for showcasing front-end experiments, games, art, and articles** — not a plug-and-play builder but a library for developers who want to build a custom portfolio CMS [citation:3]. **Requires Node.js, PostgreSQL, and optionally Rust** for the server and builder [citation:3]. **Best for developers** wanting full control over their portfolio's architecture, accepting the setup complexity of a custom CMS [citation:3].

### Additional Strong Open-Source Options

- **Astro Storyblok Portfolio Starter** — Template for running a portfolio site on Storyblok CMS with Astro, including RSS, sitemaps, OpenGraph image generation, and SSR previews for real-time editing [citation:13]. Best for designers wanting a CMS-backed portfolio with visual editing.
- **Webgen** — Super simple web builder using Markdown, HTML, and EJS templates, perfect for resumes or GitHub Pages as a Jekyll alternative . Best for developers wanting the simplest possible portfolio generation.
- **OrbitPage** — Self-hosted portfolio builder with Docker deployment, multi-language dashboard (14 languages), QR codes, and theme customization [citation:10]. Best for self-hosters wanting a feature-rich portfolio platform.

**Frameworks for building custom systems**: Combine **Open Bento** for a Bento-style link portfolio owned via GitHub, **Silex** for visual drag-and-drop static site building, **Microfolio** for a privacy-first photography portfolio with excellent performance, **CodeFX** for a modular framework that grows from portfolio to community, and **Astro templates** for quick static portfolio deployment — to build a portfolio stack tailored to your need for visual editing versus code control, and static versus full-stack deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Portfolio builders differ significantly in deployment model, data ownership, and technical complexity. **Open Bento exists specifically because Bento.me shut down** — it offers ownership and permanence over convenience, with data going directly from browser to GitHub [citation:1]. **Silex is AGPL-licensed** — review terms if building a commercial product on top of it [citation:14]. **Microfolio is privacy-by-construction** with no cookies or analytics, but requires Node.js 22.13+ and pnpm 11+ [citation:8]. **CodeFX's modular architecture** means you configure what you need, but the flatfile database option is limited to static deployments [citation:12]. **Foil is a CMS library, not a builder** — it requires Rust, Node.js, and PostgreSQL to run [citation:3]. **Self-hosting shifts responsibility to you** — domain configuration, SSL, and backups become your operations, not a vendor's.
- Self-hosted open-source solutions require proper deployment configuration (GitHub Pages for Open Bento, Node.js for Microfolio and CodeFX), and awareness that static portfolios cannot support dynamic features like comments or analytics without additional services.

---

**Made for designers, photographers, developers, and creators choosing portfolio builders they can own and control.**
Let's make portfolio website building more open, ownership-first, and permanence-focused.
