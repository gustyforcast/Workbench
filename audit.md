# GitHub Portfolio Audit — Tim Deacon (@gustyforcast)

_Generated 2026-09-25. Covers all 17 repos visible under the gustyforcast account._

---

## Step 1 — Access

All 17 repos (3 public, 14 private) were accessible once each private repo was added to the session scope. No repos required owner-level changes to inspect.

The public repos visible without authentication: **Workbench**, **Advent\_of\_code**, **config**.

---

## Step 2 — Repo inventory

| Repo | Visibility | Language | Last push | README? | What it is |
|---|---|---|---|---|---|
| Workbench | public | — | 2026-09-25 | Placeholder (11 bytes) | Planning hub (this repo) |
| agent-sandbox | private | Python / Nix | 2026-09-22 | Minimal | GitHub-centred Claude agent loop experiments |
| PhotoFlow | private | Swift | 2026-09-05 | **No** | macOS photo ingest and archive app |
| dev\_portfolio | private | TypeScript / Python | 2026-07-23 | No (has CLAUDE.md) | Monorepo: Next.js 15 portfolio site + photo CLI tools |
| StillTime | private | Swift | 2026-07-09 | **No** | SwiftUI Pomodoro timer + AI-audio meditation app (iOS) |
| Idea-engine | private | Python | 2026-07-06 | **No** | Elegant Claude-powered idea-scoring pipeline (stdlib-only) |
| app\_dev\_tool | private | TypeScript / JS | 2026-06-22 | Yes (wrong name) | Paper-trading planner + Cloudflare backend (repo name is misleading) |
| avofund-app | private, **archived** | Swift / TypeScript | 2026-02-22 | Yes (10 KB) | Fintech iOS budgeting app with Basiq banking API |
| Advent\_of\_code | public | Python | 2026-01-22 | Unknown (unreadable via API) | AoC puzzle solutions |
| swift-learning | private | — | 2025-12-16 | **No** | **Empty repo** |
| tcp-invoices | private | Python / Django | 2025-06-08 | Stub (14 bytes) | Django invoice generator for band/gig calendar (ATO-compliant) |
| baby\_sleep\_sounds | private | — | 2025-06-07 | **No** | **Empty repo** |
| photo-worker | private | TypeScript | 2025-06-03 | **No** | Cloudflare Worker that serves photos for dev\_portfolio |
| avofund-landing | private, **archived** | HTML | 2025-05-21 | Stub (17 bytes) | Static landing page for Avofund |
| avofund-email-worker | private | TypeScript | 2025-05-21 | Stub (22 bytes) | Cloudflare email worker for Avofund backend |
| config | public | unknown | 2024-03-08 | Unknown | Dotfiles / shell config (public, unaudited) |
| JetBrains-Academy | private, **archived** | Python | 2022-11-10 | Yes (416 bytes) | JetBrains Academy exercises (Bill Splitter, Hangman, etc.) |

_Not counted: `JohnClema/pretty-fly-for-a-gemini` — not owned by this account._

---

## Step 3 — Sorted categories

### 🟢 Showcase — pin and polish

| Repo | Reason | Missing |
|---|---|---|
| **Idea-engine** | Elegant single-file Python LLM pipeline (no pip installs, Claude + Ollama + SQLite + self-contained HTML dashboard). Shows Python automation craft clearly. | README, licence, one usage screenshot of the dashboard |
| **Advent\_of\_code** | Already public; shows algorithmic Python fluency annually. | A proper README (year coverage, language, brief approach notes) |

**Engineering showcase — planned repo:** There are currently no repos demonstrating subsea engineering work. The most differentiating addition would be a new public Python library implementing DNV subsea design checks (pipeline wall thickness to DNV-ST-F101, free-span VIV screening, on-bottom stability per DNV-RP-F109), with a pytest suite and worked examples. See the action checklist below.

---

### 🟡 Archive — keep but make dormant / unlisted

| Repo | Reason |
|---|---|
| **avofund-app** | Already archived. Rich, well-documented iOS+backend fintech project; keep as a historical record of your iOS depth. |
| **avofund-landing** | Already archived. Static HTML; absorbed into avofund-app history. |
| **avofund-email-worker** | Cloudflare TS email backend for Avofund. Useful for reference; archive it alongside the app. |
| **tcp-invoices** | Niche but real: Django invoice generator for gigging musicians. Interesting Python/Django work but too domain-specific to showcase. Archive. |
| **photo-worker** | Cloudflare Worker that backs dev\_portfolio; has `node_modules` committed (messy). Archive or absorb into dev\_portfolio. |
| **JetBrains-Academy** | Already archived. Python learning record from 2022; worth keeping as a timestamp of your Python start. |

---

### 🔒 Private — keep private as-is

| Repo | Reason |
|---|---|
| **StillTime** | Commercial iOS app — source stays private permanently. Showcased via the App Store. |
| **PhotoFlow** | Commercial macOS app — source stays private permanently. In development. |
| **Workbench** | This planning hub. Currently public with a stub README; the CLAUDE.md gives it purpose. |
| **dev\_portfolio** | Active working space: Next.js portfolio site + photo CLI tools + Hugo archive. Too scattered to showcase directly; keep private. |
| **agent-sandbox** | Active Claude agent experiments; private experimentation space. |
| **app\_dev\_tool** | Paper-trading planner with Cloudflare backend. Confusingly named (the README title is "Investing\_tool"). Keep private until cleaned up. |
| **config** | Public dotfiles; harmless as-is, not worth promoting. |

---

### 🗑️ Delete candidates

| Repo | Reason |
|---|---|
| **swift-learning** | Completely empty — no files, no commits beyond initialisation. |
| **baby\_sleep\_sounds** | Completely empty — no files, no commits beyond initialisation. |

---

## Step 4 — Recommended pinned profile (after polish)

Suggested pinned set (GitHub allows 6). Commercial apps are showcased via the App Store / Mac App Store; only public repos are pinned here.

1. `Idea-engine` — Python automation
2. `Advent_of_code` — Python
3. _(planned)_ `dnv-subsea-checks` — Python / subsea engineering
4. `Workbench` — portfolio meta / planning hub _(optional)_

---

## Public repo policy

Commercial apps (currently StillTime and PhotoFlow, and any future paid app) have their source code kept private permanently. Public repos are limited to tools, libraries, and learning work. The App Store and Mac App Store serve as the public showcase for commercial apps.

---

## Action checklist

- [ ] **Delete** `swift-learning` and `baby_sleep_sounds`
- [ ] **Archive** `avofund-email-worker`, `tcp-invoices`, `photo-worker`
- [ ] **Make public + add README** for `Idea-engine`
- [ ] **Add meaningful README** to `Advent_of_code`
- [ ] **Add licence** to `Idea-engine` and `dnv-subsea-checks`
- [ ] **Add a usage screenshot or demo GIF** to `Idea-engine`
- [ ] **Rename** `app_dev_tool` to something accurate (e.g. `paper-trading-tool`)
- [ ] **Create** `dnv-subsea-checks` — public Python library for DNV pipeline design checks (wall thickness DNV-ST-F101, free-span VIV, on-bottom stability DNV-RP-F109) with pytest suite and worked examples
- [ ] **Pin** showcase repos once polished
- [ ] **Identify** self-contained components in StillTime/PhotoFlow that could be extracted as public Swift packages
