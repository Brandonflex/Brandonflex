<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2600&pause=800&color=3B82F6&center=true&vCenter=true&width=620&height=46&lines=Frontend+Engineer+%E2%80%94+React+%26+TypeScript;Local-first+apps+with+a+real+CI+gate;Shipped+a+50-piece+storefront+to+a+live+client;Nairobi%2C+Kenya+%F0%9F%87%B0%F0%9F%87%AA" alt="Frontend Engineer — React & TypeScript · Local-first apps with a real CI gate · Shipped a 50-piece storefront to a live client · Nairobi, Kenya" />

# Flex Brandon

### Frontend Engineer — React &amp; TypeScript

📍 Nairobi, Kenya &nbsp;·&nbsp; 🟢 Open to frontend work

<br />

<a href="https://www.linkedin.com/in/flex-brandon" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="mailto:brandonflex108@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email brandonflex108@gmail.com" /></a>&nbsp;
<a href="https://github.com/Brandonflex" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>&nbsp;
<a href="https://www.instagram.com/brand0ne.io/" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>&nbsp;
<a href="https://www.pinterest.com/brand0neflex/" target="_blank"><img src="https://img.shields.io/badge/Pinterest-BD081C?style=for-the-badge&logo=pinterest&logoColor=white" alt="Pinterest" /></a>

</div>

<br />

I build frontend systems that **stay correct after the demo**. Strict TypeScript, a test suite behind
every behaviour, and a CI gate that fails the build instead of trusting it. Two shipped products
below, both live, both passing their pipelines.

**The short version:** React + TypeScript product UIs, framework-free commerce sites engineered for
markets where card-first checkout is the wrong default, and quality enforced as a build step rather
than a habit.

---

## Shipped

### 🟦 Motif — local-first productivity suite

> Tasks, projects, focus and analytics in one workspace. **No account, no subscription, no analytics,
> nothing leaves the browser.**

<a href="https://motif-productivity-suite.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/LIVE_DEMO-motif--productivity--suite.vercel.app-000?style=for-the-badge&logo=vercel&logoColor=white" alt="Open the live demo of Motif" /></a>&nbsp;
<a href="https://github.com/Brandonflex/motif-productivity-suite" target="_blank"><img src="https://img.shields.io/badge/SOURCE-motif--productivity--suite-181717?style=for-the-badge&logo=github&logoColor=white" alt="Motif source code" /></a>&nbsp;
<img src="https://github.com/Brandonflex/motif-productivity-suite/actions/workflows/ci.yml/badge.svg" alt="Motif CI status" />

| | |
| :-- | :-- |
| **Stack** | React 19.2 · TypeScript 6 (strict) · Vite 8 · Tailwind 3.4 · Vitest 5 · Zod 4 |
| **Verified** | ✅ **275 tests passing** across 30 suites · typecheck · ESLint · Stylelint · 48 contrast checks |
| **Scale** | ~11,800 lines of app code + ~4,200 lines of tests · 12 clean CI runs |
| **Data** | Plain JSON in `localStorage` (`motif:workspace:v3`) — exportable, importable, versioned |
| **Network** | Zero HTTP requests after load. No backend, no tracker, strict CSP enforced at the edge |
| **License** | MIT |

**What's in it**

- **Four views of one dataset** — list, Kanban board with WIP limits, Eisenhower matrix, and a
  seven-day schedule canvas with native HTML5 drag-and-drop.
- **Natural-language quick add** — type *"draft proposal in 3 days #work !high"* and it parses the
  date, tag and priority.
- **A planning ritual, not a to-do list** — morning planning with an over-capacity warning,
  auto-scheduled blocks inside your working hours, a pomodoro focus timer, and an evening shutdown
  that rolls unfinished work into tomorrow.
- **No-code automations** — Trello/Butler-style rules: *when a task is created/completed/moved,
  then set its priority, status, tags or schedule it out.*
- **Insights you can act on** — four weeks of momentum, a completion heatmap, focus split by task,
  capacity rollups and a weekly review.
- **`.ics` export** — commit the plan and drop it straight into a real calendar.
- **Design tokens with teeth** — `npm run check:tokens` walks all 45 colour tokens in light and dark
  and **fails the build on a contrast regression**, so "make it prettier" can't make it unreadable.

**The thinking behind it:** [why Motif exists](https://github.com/Brandonflex/motif-productivity-suite/blob/main/about/why-motif-exists.md) ·
[the promise](https://github.com/Brandonflex/motif-productivity-suite/blob/main/about/the-promise.md) ·
[building it](https://github.com/Brandonflex/motif-productivity-suite/blob/main/about/building-it.md)

<br />

### 🛍️ Bagged Up — 50-piece boutique storefront, shipped to a live client

> A curated handbag boutique engineered for the Kenyan market. **Framework-free: plain HTML, CSS and
> vanilla JS, zero runtime dependencies.**

<a href="https://baggedup-seven.vercel.app" target="_blank"><img src="https://img.shields.io/badge/LIVE_STOREFRONT-baggedup--seven.vercel.app-161616?style=for-the-badge&logo=vercel&logoColor=white" alt="Open the live Bagged Up storefront" /></a>&nbsp;
<a href="https://github.com/Brandonflex/Bagged.up" target="_blank"><img src="https://img.shields.io/badge/SOURCE-Bagged.up-181717?style=for-the-badge&logo=github&logoColor=white" alt="Bagged Up source code" /></a>&nbsp;
<img src="https://github.com/Brandonflex/Bagged.up/actions/workflows/ci.yml/badge.svg" alt="Bagged Up CI status" />

| | |
| :-- | :-- |
| **Stack** | Hand-written HTML/CSS/JS · no framework · no bundler · no server code · zero runtime deps |
| **Verified** | ✅ **38/38 site checks + 25/25 behaviour tests** · HTML validation · ESLint · TS typecheck over JS · **CI green on `main`** (72 runs to date) |
| **Scale** | 61 pages (11 root + 50 product) · 2,134 lines of CSS · 1,096-line single-IIFE app · 141 product photos |
| **Security** | Strict CSP, `X-Frame-Options: DENY`, HSTS, sanitised inputs against DOM XSS |
| **Hosting** | Vercel + Cloudflare Workers Static Assets, free edge CDN, zero database |
| **Status** | **Handed over to the business owner, October 2026** — with a non-technical handover package |

**Why it's built that way** — Western commerce platforms make assumptions that fail Kenyan shoppers,
so the checkout was designed around how people here actually pay:

- **M-Pesa and cash-on-delivery, not cards** — forcing a card form drives abandonment, so checkout
  routes to WhatsApp, where stock, dimensions and delivery are confirmed by a human.
- **Real Nairobi logistics** — KSh 250 flat next-day in Nairobi, KSh 400 upcountry (2–3 days),
  **free over KSh 5,000** with a live progress bar.
- **Concrete dates, not "standard shipping"** — the cart computes and displays the actual arrival
  date for the shopper's zone.
- **Zero operational overhead** — a pure static export the owner hosts for free, with a handover
  package (`START-HERE.html`, price list, step-by-step deploy instructions) written for a
  non-technical reader.

**Also in the box:** occasion finder, instant category filters, keyboard- and swipe-accessible
lightbox galleries, saved items and recently-viewed rails in `localStorage` (no cookies, no
accounts), per-product verified-buyer reviews, FOUC-free system-aware dark theme, clean URLs
(`/shop/<slug>`) synchronised across Vercel, Cloudflare and `sitemap.xml`.

<br />

### 🧪 Earlier work

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [**Self Check-out System**](https://github.com/Brandonflex/Self-Check-out-system) | Retail self-checkout — Home, Products, Checkout and Navbar across multiple routes | React 19 · React Router 7 · CRA |
| [**Password Generator**](https://github.com/Brandonflex/PasswordGenerator---001) | A simple password generator in plain HTML, CSS and JavaScript | HTML · CSS · JS |
| [**Basic BMI**](https://github.com/Brandonflex/Basic-BMI) | The first thing I ever shipped (Dec 2024) — where the habit of finishing started | HTML · CSS |

---

## Engineering standards

The pattern in both projects is the same: **one command runs the whole gate, and CI runs the same
command on every push.** Nothing merges on vibes.

```bash
npm run verify   # lint → test → build
```

| Gate | Motif | Bagged Up |
| :-- | :-- | :-- |
| **Typecheck** | `tsc` strict, app + node configs | `tsc` over plain JS via `jsconfig.json` |
| **Lint** | ESLint 9 + `jsx-a11y` + `react-hooks` | ESLint 10 |
| **Style / markup** | Stylelint on every CSS file | `html-validate` on all 61 pages |
| **Design integrity** | 45 tokens, 48 contrast checks, build fails on regression | Design + layout checks (`check-design`, `check-layout`) |
| **Tests** | 275 passing, Vitest + Testing Library | 63 checks, JSDOM + Node harness |
| **Build** | Verified static build, SEO files rewritten to canonical origin | Verified static build |
| **Supply chain** | `npm ci` pinned | Actions pinned to immutable SHAs, read-only permissions, Dependabot weekly |

Accessibility and reduced-motion behaviour are built into the components, not patched on later.
Security headers and CSP are set at the edge, so a future mistake can't quietly undo them.

---

## Stack

| Area | Tools |
| :-- | :-- |
| **Core** | React 19 · TypeScript (strict) · JavaScript (ES2022+) · Vite · React Router 7 |
| **UI & styling** | Tailwind CSS · Radix UI (via `@blinkdotnew/ui`) · token-based design systems · `lucide-react` · hand-written CSS for static sites |
| **Forms & validation** | React Hook Form · Zod 4 · `@hookform/resolvers` |
| **State & data** | React Context + providers · `localStorage` persistence with explicit migration paths · local-first architecture |
| **Testing** | Vitest · Testing Library · `user-event` · JSDOM · `html-validate` · Puppeteer (tooling) |
| **Quality** | ESLint · Stylelint · Prettier · EditorConfig · design-token contrast checks |
| **CI/CD & hosting** | GitHub Actions · Vercel · Cloudflare Workers Static Assets · strict CSP / security headers |
| **Commerce specifics** | M-Pesa & COD checkout flows · WhatsApp handoff · SEO (OG, Twitter Cards, canonicals, sitemaps) · `.ics` generation |

### On working with AI tooling

I use AI agents as a build multiplier, not a crutch — **they draft, the pipeline judges.** Architecting
the system, defining the contracts and reviewing every diff stays with me; the gate above is what makes
that safe. It's how one person ships a 275-test product suite and a 61-page storefront solo, at a
standard that would normally take a team.

---

## Currently

- 🔧 Extending **Motif** — deeper automations and richer insight views
- 🧭 Exploring **edge-rendered commerce** — static speed with dynamic data
- 📚 Sharpening **testing and a11y** as first-class deliverables, not afterthoughts

**I'm open to frontend roles and contract work.** Best fit: product engineering where TypeScript,
design systems and CI discipline are already taken seriously — or where they need someone to
introduce them.

---

## Reach me

| | |
| :-- | :-- |
| 📧 **Email** | [brandonflex108@gmail.com](mailto:brandonflex108@gmail.com) |
| 💼 **LinkedIn** | [linkedin.com/in/flex-brandon](https://www.linkedin.com/in/flex-brandon) |
| 🐙 **GitHub** | [@Brandonflex](https://github.com/Brandonflex) |

Replies within a day. Send the repo, the bug or the brief — I'd rather look at the problem than talk
about it.

---

<div align="center">

<img src="https://ghchart.rshah.org/3B82F6/Brandonflex" alt="Brandon's GitHub contribution chart" width="100%" />

<br />

<img src="https://img.shields.io/github/followers/Brandonflex?style=flat-square&logo=github&label=Followers&color=3B82F6" alt="GitHub followers" />&nbsp;
<img src="https://img.shields.io/github/last-commit/Brandonflex/motif-productivity-suite?style=flat-square&logo=git&label=Last%20commit&color=3B82F6" alt="Last commit on Motif" />&nbsp;
<img src="https://img.shields.io/github/license/Brandonflex/motif-productivity-suite?style=flat-square&label=Licence&color=3B82F6" alt="MIT licence" />&nbsp;
<img src="https://img.shields.io/badge/built_with-care-3B82F6?style=flat-square" alt="Built with care" />

<br /><br />

<sub>Built and maintained by <a href="https://github.com/Brandonflex">Flex Brandon</a> · Nairobi, Kenya ·
last updated October 2026</sub>

</div>
