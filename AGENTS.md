# AGENTS.md — jonathanmccallum-pl (Polish mirror of jonathanmccallum.com)

Polish mirror site. Same theme and design as the main site (Paper Light),
content translated into Polish, meaning-first. Repo: streamjonathan/jonathanmccallum-pl.
Live: jonathanmccallum-pl.pages.dev (Jonathan approved all 50 mirrors live, 22 Nov 2026).
Custom subdomain pl.jonathanmccallum.com comes later, via the dashboard.

## Mission

Mirror jonathanmccallum.com in Polish — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## Publishing

Jonathan approved all 50 language mirrors live (22 Nov 2026), so this mirror
goes live on jonathanmccallum-pl.pages.dev with its 5 proof articles.
The custom subdomain pl.jonathanmccallum.com is a later dashboard step. New articles stay drafts
until he approves them.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: informal "ty" throughout (matches the French proof's "tu"). FLAG
  for Jonathan: if he prefers formal Pan/Pani, every "ty" form changes.
- Names (never vary): Aslan, Narnia, Digory, Tirian unchanged; Lucy → Łucja
  (Polkowski's rendering in the published Polish Narnia — flagged). Book titles
  use the published Polish titles (Polkowski, Media Rodzina): Opowieści z Narnii,
  Siostrzeniec czarodzieja, Trylogia kosmiczna, Ostatnia bitwa. The Great Divorce
  → Wielki rozwód is FLAGGED — no published Polish edition verified.
- Bible verses: the bread/water of life lines are Jonathan's paraphrase — chleb
  życia / woda życia — never quoted as Scripture. No direct Lewis quotations.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
