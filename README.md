# FundedNext Content Virality Playbook (V5)

Internal RM field manual for growing FundedNext's Instagram followers and YouTube
views/subscribers, built on the live 2026 platform algorithm models.

> **Internal use only.** Deploy to a **private** repo / access-controlled host.

## What it is
A single self-contained static page (`index.html`, no build step, no dependencies).
Covers the 4-phase distribution model, per-platform algorithm cheat sheet
(YouTube long-form + Shorts, Instagram Reels, Facebook, TikTok, X), the Cliffhanger
System (short-form → full video), content pillars, hook toolkit, first-hour tactics,
packaging, the 2026 IG growth targets, and FN brand guardrails.

## Source of truth
Content is generated from the `platform-content-virality` skill
(`~/.claude/skills/platform-content-virality/`), calibrated **July 2026**.
When the skill updates, **regenerate this page** rather than hand-editing numbers,
so it can't drift from the engine.

## Local preview
Open `index.html` directly, or:
```
python3 -m http.server 4321
```
then visit http://localhost:4321

## Deploy (Vercel)
No config needed — it's a static site. Import the repo in Vercel; it serves `index.html`
at the root. Keep the Vercel project's deployment protection on for an internal doc.
