<h1 align="center">Morhaf&nbsp;Ghziel</h1>

<p align="center">
  <b>Full-stack developer who ships.</b>
</p>

<p align="center">
  I design and build web apps end to end — React, Next.js and TypeScript on the front,<br>
  APIs and databases behind them. Most of my work goes live under someone else's logo.
</p>

<p align="center">
  <a href="https://www.morhaf.me"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-morhaf.me-E0A87E?style=flat-square&labelColor=0D1117"></a>
  <a href="https://www.linkedin.com/in/morhaf-ghziel-a720a72b9/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-E0A87E?style=flat-square&labelColor=0D1117"></a>
  <a href="https://x.com/MorhafGhz"><img alt="X" src="https://img.shields.io/badge/X-@MorhafGhz-E0A87E?style=flat-square&labelColor=0D1117"></a>
  <a href="mailto:ghzielmorhaf@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Say_hello-E0A87E?style=flat-square&labelColor=0D1117"></a>
</p>

<p align="center">
  <img alt="Riyadh, GMT+3" src="https://img.shields.io/badge/Riyadh-GMT%2B3-0D1117?style=flat-square&labelColor=0D1117&color=6E7681">
  <img alt="Remote worldwide" src="https://img.shields.io/badge/Working-Remote,_worldwide-0D1117?style=flat-square&labelColor=0D1117&color=6E7681">
  <img alt="Open to work" src="https://img.shields.io/badge/Status-Open_to_new_projects-0D1117?style=flat-square&labelColor=0D1117&color=6E7681">
</p>

---

### About

Full-stack developer, five years in, based in Riyadh and working remotely worldwide.

My centre of gravity is the front end — React and Next.js, where I care about how fast a thing
feels and how easy it stays to change six months later. I work across the backend too: APIs,
databases and the server-side logic that makes a feature complete rather than a demo.

Most of my paid work has been building and shipping entire sites for Saudi companies — design
through deployment, usually as the only developer on the project. That means Arabic and RTL
aren't a checkbox I tick at the end; they set the constraints from the first commit.

---

### In production

Real sites, real clients, live right now.

| | What it is | Stack | |
|---|---|---|---|
| **Omdah Studio** | Bilingual RTL landing site and a bespoke CMS for a Riyadh visual-production studio — the studio edits every project, reel and line of copy itself | Next.js · Supabase · Postgres RLS · Signed uploads | [Live](https://www.omdah.sa) · [Code](https://github.com/MorhafGhziel/OmdahStudio-Landing) |
| **Etar** | Arabic-first store for framed art prints, with ClickPay checkout and a 16-page admin | Next.js · Express · Prisma · PostgreSQL · JWT | [Live](https://eyetar.com) |
| **Alpha Factory** | Production management system: roles, boards, invoices, PayPal and bot alerts | Next.js · Prisma · PostgreSQL · PayPal · Telegram API | [Live](https://www.alphafactory.net) · [Code](https://github.com/MorhafGhziel/Alpha-Factory) |
| **Snaya** | Arabic-first corporate site for a Saudi influencer-management agency | Next.js · Three.js · Framer Motion · Lenis | [Live](https://www.snaya.sa) · [Code](https://github.com/MorhafGhziel/elsina3ya) |
| **Alpha Factory Landing** | Arabic marketing site built around one path: visitor to signup | Next.js · Tailwind · RTL | [Live](https://www.xalphafactory.com) |
| **Iedar** | Corporate site for a Saudi architectural design studio | Next.js · Framer Motion · RTL | [Live](https://www.iedar.sa) · [Code](https://github.com/MorhafGhziel/Idear_Landing) |

---

### Built for myself

Where I go when I want to find out whether something is actually hard.

| | What it is | Stack | |
|---|---|---|---|
| **Archy** | Describe an app in one sentence, get a live entity diagram — then Prisma, TypeScript and SQL generated from that same graph. The canvas is hand-built; there is no diagramming library in the project | Next.js · Server Actions · Prisma · Neon · Gemini | [Live](https://devflow-ai-mu.vercel.app/) · [Code](https://github.com/MorhafGhziel/devflow-ai) |
| **Lumen** | Documents and an infinite canvas in one workspace, with an AI sidebar that reads the open page | Next.js · Supabase · HTML5 Canvas · Gemini | [Live](https://lumen-woad-nine.vercel.app/) · [Code](https://github.com/MorhafGhziel/lumen) |
| **AI CV Generator** | Upload a PDF, paste a job post, get an ATS-ready CV tailored to it | Next.js · MongoDB · Prisma · NextAuth · Gemini · Groq | [Live](https://ai-cv-generator-opal.vercel.app/) · [Code](https://github.com/MorhafGhziel/ai-cv-generator) |

---

### Notes from the work

A few things these builds actually taught me — the kind that don't fit in a badge.

- **Arabic sets the constraints, not the layout grid.** A headline reveal has to mask *words*,
  not characters — splitting a character breaks the joining forms and renders nonsense. Arabic
  is never letterspaced and has no uppercase, so every Latin-only type primitive needs an Arabic
  twin rather than a `lang` swap.
- **Font fallback fails silently.** A font with no Arabic coverage doesn't error; the browser
  just substitutes. I found index numerals rendering in Times New Roman by asking Chrome which
  face actually drew each glyph — CSS only reports what you asked for, not what you got.
- **Big files never touch the backend.** Video reels run to 45MB and serverless request bodies
  cap far below that, so the server mints a signed URL and the browser writes straight to object
  storage.
- **Two-tier data access.** Row-level security makes reads safe with the browser's key; every
  mutation goes through a server route holding the service role, so the client never carries a
  credential that can change anything.

---

### What I work with

**Front end**
`React` `Next.js (App Router, Server Actions)` `TypeScript` `Tailwind CSS` `Framer Motion` `CSS animation & View Transitions` `Radix UI` `RTL / Arabic layout`

**Backend & data**
`Node.js` `Express` `REST APIs` `PostgreSQL / Neon` `Supabase` `Prisma` `MongoDB` `Auth (Clerk, NextAuth, JWT)` `Payments (ClickPay, PayPal)` `S3 storage & uploads` `Zod`

**Design & tooling**
`Figma` `Git & GitHub` `Vercel` `Strict TypeScript & ESLint` `Three.js` `GSAP` `Canvas & SVG` `Gemini / Groq`

---

<div align="center">

<img height="150" alt="Morhaf's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=MorhafGhziel&show_icons=true&rank_icon=github&hide_border=true&bg_color=00000000&title_color=E0A87E&icon_color=E0A87E&text_color=6E7681&hide_title=true">
<img height="150" alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MorhafGhziel&layout=compact&langs_count=8&hide_border=true&bg_color=00000000&title_color=E0A87E&text_color=6E7681">

</div>

---

### Get in touch

Email is the fastest way to reach me — I read everything and reply within a day.
Tell me what you're building, roughly when you need it, and what success looks like.

**[ghzielmorhaf@gmail.com](mailto:ghzielmorhaf@gmail.com)** · **[morhaf.me](https://www.morhaf.me)**

<sub>Arabic (native) · English (professional) · Riyadh, GMT+3 · Open to new projects and full-time roles</sub>
