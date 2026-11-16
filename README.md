<!-- Profile README for @nferdazel — Fredi · Qouver -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f172a,100:1e3a5f&text=Hi,%20I'm%20Fredi%20—%20Qouver&fontColor=ffffff&fontSize=36&desc=Code%20·%20Coffee%20·%20Commit%20—%20repeat&descAlignY=68&descAlign=50&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://github.com/nferdazel"><img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&size=16&duration=3000&pause=800&color=94A3B8&center=true&vCenter=true&width=600&lines=Systems+Prospector+%C2%B7+Solo+Developer+%C2%B7+Indonesia;Nim+%2B+Postgres+%2B+Svelte;Building+Majadu+%2C+SDS+%26+KRAN;Writing+Nim+%26+Nimony+books" alt="" aria-hidden="true" /></a>
</p>

<p align="center">
  <a href="https://qouver.com"><img src="https://img.shields.io/badge/qouver.com-umbrella-0f172a?style=for-the-badge" /></a>
  <a href="https://qouver.com/projects/skyward"><img src="https://img.shields.io/badge/Skyward-Archived-64748b?style=for-the-badge&logo=flutter&logoColor=white" /></a>
  <a href="https://sds.qouver.com"><img src="https://img.shields.io/badge/SDS-Live-10b981?style=for-the-badge&logo=vue.js&logoColor=white" /></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=nferdazel&left_color=%230f172a&right_color=%230ea5e9" />
</p>

---

### 🧑‍💻 About Me

Hey, I'm **Fredi** — **Systems Prospector** behind [**Qouver**](https://qouver.com). Solo-developer, cost-conscious, all-rounder.

I don't run a team — I run systems. From airline-tycoon simulation to badminton session ops to SDS compliance tools, I design, ship, and operate end-to-end: **Svelte/Vue/Flutter on the front, Nim + Postgres on the back, all deployed on a single VPS.**

> *Philosophy:* preserve intent, ship the simplest correct solution, automate the rest. `Code → ship → observe → refine.`

- 🌏 Based in Indonesia · building for real communities (not just demos)
- 🎯 Currently focused on: **Majadu** (badminton ops), **SDS Management** (Bayer), **KRAN** (core banking, KSP first slice), **Nim & Nimony books**
- ✍️ Writing on [Medium @nferdazel](https://medium.com/@nferdazel)
- ☕ Fuel: coffee, clean code, and zero-downtime deploys

---

### 🏗️ What I Build — The Qouver Ecosystem

> Live systems on `qouver.com`, archived ones kept as case studies, plus the public books. Solo-built, production-run.

| # | Project | What it is | Stack | Status |
|---|---------|------------|-------|--------|
| **01** | [**Majadu**](https://qouver.com/projects/majadu) — *Session Ops Engine* | Club operations app: court scheduling (5-phase engine), live scoring & SSE streams, Glicko-1-lite rating + 8-tier bands, tournament brackets. SvelteKit SPA in front of a Nim API on one Postgres, 76 operations generated from OpenAPI, schema-based multi-tenancy. | `Nim` · `Svelte` · `Postgres` · `OpenAPI` | 🟢 **Live** |
| **02** | [**Qouver Web**](https://qouver.com) — *Umbrella Home* | Company site — 100% static HTML prerendered server-side, no JS. Swiss editorial design. | `SvelteKit` · `Nim` · `Caddy` | 🟢 **Live** |
| **03** | [**SDS Management**](https://sds.qouver.com) — *Compliance* | SDS/MSDS lifecycle: chemical versioning, GHS pictograms, HTML→PDF (Chromium headless), bulk ZIP. | `Vue 3` · `Element Plus` · `Go` · `Postgres` | 🟢 **Live** |
| **04** | [**KRAN**](https://github.com/nferdazel/kran) — *Core Banking* | Core banking for Indonesian cooperatives. First slice is KSP (simpan pinjam): members, savings, loans with maker/checker, SHU, RAT-class reporting. BPR/BPRS and syariah packages are planned, not built. Strict double-entry GL (no float money), outbox pattern. | `Nim` · `Postgres` · `SvelteKit` | 🟡 **In build** |
| **05** | [**seather**](https://github.com/nferdazel/seather) — *CI/CD Lab* | Hands-on Flutter CI/CD pipeline — GitHub Actions, release automation, production workflows. | `Flutter` · `GitHub Actions` | 🔵 **Open Source** |
| **06** | [**nim-id**](https://github.com/nferdazel/nim-id) — *Nim Book* | Learning Nim in Indonesian and English; every example compiled and verified in CI. | `Nim` · `CI` | 🔵 **Open Source** |
| **07** | [**nimony-id**](https://github.com/nferdazel/nimony-id) — *Nimony Book* | Hands-on book for programmers learning Nimony, built and verified against one pinned commit, two editions. | `Nimony` · `CI` | 🔵 **Open Source** |
| **08** | [**Skyward**](https://qouver.com/projects/skyward) — *Airline Tycoon* | Authoritative simulation: fleet, routes, economy, bank/loans, world-tick. Go backend as sole engine, Flutter client as a pure viewer on web and desktop. | `Go` · `Postgres` · `Flutter` | ⚪ **Archived** |
| **09** | [**M-DEF**](https://qouver.com/projects/mdef) — *Ranking Analytics* | Leaderboard and analytics for a real badminton community, on a custom rating engine that weighed how convincingly you won. Ran in production; its ideas now live inside Majadu. | `Flutter` · `Supabase` · `Postgres` | ⚪ **Archived** |

<details>
<summary>📦 More in <code>/Projects</code> (local / research)</summary>

- `sds-monorepo` — ships its Go backend inside `apps/api` (stdlib `net/http` + `pgx/v5`, no framework bloat), not as a separate repo
- `fond` — private operations instrument for freelance work and a self-hosted server (`Nim` + `SvelteKit`)
- `anomali_detection` — pair/bracket anomaly research + SQL dumps (badminton) · *folded into Majadu*
- `ohsera` / `ojan` — audit reports & agentic-AI POC notes (private, not on GitHub)

</details>

---

### 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nim,ts,java,postgres,svelte,vue,flutter,dart,linux,githubactions&perline=10&theme=dark" />
</p>

| Layer | Tools |
|-------|-------|
| **Languages** | Nim 2.4 (Mummy) · TypeScript 6 · Java · Dart |
| **Backend & Data** | PostgreSQL 18 (`pgx/v5`) · OpenAPI |
| **Frontend & UI** | SvelteKit 3 / Svelte 5 · Vue 3 (Element Plus) · Flutter |
| **Infra & Ops** | Rocky Linux 9 · Podman Quadlet (systemd) · Caddy (TLS + reverse proxy) · GitHub Actions |

---

### 🧮 GitHub Stats

<table align="center">
  <tr>
    <td width="50%"><img width="100%" src="https://github-readme-stats.vercel.app/api?username=nferdazel&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&card_width=430" alt="GitHub stats" /></td>
    <td width="50%"><img width="100%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nferdazel&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&card_width=430" alt="Top languages" /></td>
  </tr>
  <tr>
    <td colspan="2"><img width="100%" src="https://streak-stats.demolab.com/?user=nferdazel&theme=tokyonight&hide_border=true" alt="Streak stats" /></td>
  </tr>
  <tr>
    <td colspan="2"><img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nferdazel&theme=tokyonight" alt="Profile details" /></td>
  </tr>
</table>

---

### 🔭 Currently

```go
var now = map[string]string{
    "building":  "KRAN — KSP first slice: savings, loans with maker/checker, SHU, RAT-class reporting",
    "shipping":  "Majadu — SSE realtime + concurrency hardening, live for real sessions",
    "operating": "SDS Management — versioned sheets, GHS pictograms, clean PDF exports",
    "writing":   "Nim & Nimony books — every example compiled and verified in CI",
    "learning":  "Nimony internals — one pinned commit, written down as it moves",
}
```

---

### 📫 Let's Connect

<p align="center">
  <a href="https://qouver.com"><img src="https://img.shields.io/badge/Web-qouver.com-0f172a?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://github.com/nferdazel"><img src="https://img.shields.io/badge/GitHub-nferdazel-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://medium.com/@nferdazel"><img src="https://img.shields.io/badge/Medium-@nferdazel-000000?style=flat-square&logo=medium&logoColor=white" /></a>
  <a href="mailto:hello@qouver.com"><img src="https://img.shields.io/badge/Email-hello@qouver.com-0ea5e9?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <em>Building systems that keep communities running — one commit at a time.</em><br/>
  <sub>© Qouver · Solo-built, production-operated.</sub>
</p>
