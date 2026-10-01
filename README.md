<div align="center">

# 👨‍💻 Sriram G S

### Developer Portfolio · Competitive Programmer · B.Tech IT

**A fast, fully static portfolio whose coding statistics update themselves every day — no backend, no build step, no runtime dependencies on third‑party APIs.**

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fgssriram.live&up_message=online&down_message=offline&label=gssriram.live&style=flat-square&logo=googlechrome&logoColor=white)](https://gssriram.live/)
[![Stats sync](https://github.com/gssriram9050/gssriram/actions/workflows/sync-codolio-stats.yml/badge.svg)](https://github.com/gssriram9050/gssriram/actions/workflows/sync-codolio-stats.yml)
[![Last commit](https://img.shields.io/github/last-commit/gssriram9050/gssriram?style=flat-square&logo=git&logoColor=white)](https://github.com/gssriram9050/gssriram/commits/main)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-automated-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosting-GitHub%20Pages-24292e?style=flat-square&logo=github&logoColor=white)

[🌐 Live Site](https://gssriram.live/) · [📄 Resume](resume.pdf) · [🧾 Sync Log](codolio-sync-log.md) · [⚙️ Workflow](.github/workflows/sync-codolio-stats.yml)

</div>

---

## 🔭 What is this?

The personal portfolio and single‑page resume of **Sriram G S** — B.Tech Information Technology student at Karpagam College of Engineering, Coimbatore, software developer, and competitive programmer.

It is one `index.html` served by GitHub Pages. A scheduled GitHub Actions workflow keeps the hero statistics current, so visitors always get plain static files and **never contact Codolio or any other API**.

## ✨ Key Features

- 🧭 **Single‑page navigation** — nine hash‑routed sections with browser back/forward support
- 📊 **Self‑updating statistics** — problems solved, contests, active days, and streak refreshed daily
- 🧾 **Audit trail** — every sync run is recorded in an append‑only Markdown log
- 🛡️ **Guarded automation** — can change only four numbers in one tagline; everything else is protected
- 🎓 **Certificate previews** — modal viewer with credential verification links
- 🎨 **Themeable** — colors, font, and content driven by one config object and CSS variables
- 🔍 **Discoverable** — Open Graph, Twitter cards, JSON‑LD, sitemap, robots rules, and `llms.txt` for AI assistants
- ⚡ **Fast by design** — static files, system fonts, zero build tooling

## 🔄 How It Works

**Visitor path**

```
🌐 gssriram.live ─► 📦 GitHub Pages ─► 📄 index.html ─► 🧭 Hash routing ─► 🖥️ Section rendered
```

**Automation path**

```
⏰ 02:00 IST / manual run
        │
        ▼
📡 Codolio profile API ─► 🧮 Derive 4 totals ─► 🔽 Round down to 10 ─► ⚖️ Compare with tagline
                                                                            │
                          ┌─────────── changed ◄────────────────────────────┤
                          ▼                                                 ▼
              ✏️ Update tagline digits                               ⏭️ Leave site untouched
                          └────────────────────┬────────────────────────────┘
                                               ▼
                       🧾 Append audit row ─► 💾 Commit as owner ─► 🚀 Pages republishes
```

## 🛠️ Tech Stack

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=html,css,js,tailwind,git,github,githubactions&perline=7" alt="HTML, CSS, JavaScript, Tailwind CSS, Git, GitHub, GitHub Actions" /></a>
</p>

| Layer | Technology |
|---|---|
| 🧱 **Markup** | HTML5 — semantic single‑page structure |
| 🎨 **Styling** | Tailwind CSS v3.4.17 (pre‑built, inlined) · CSS custom properties |
| ⚙️ **Logic** | Vanilla JavaScript — routing, rendering, certificate modal, custom cursor |
| 🔣 **Icons** | Lucide 0.263.0 (jsDelivr CDN) |
| 🔤 **Typography** | System font stack — no web‑font requests |
| 🤖 **Automation** | GitHub Actions · Python 3 standard library (zero dependencies) |
| 🚀 **Hosting** | GitHub Pages · custom domain via `CNAME` |

## 🗺️ Site Sections

| Route | Section |
|---|---|
| `/#home` | 🏠 Hero & about |
| `/#education` | 🎓 Education |
| `/#skills` | 🧠 Skills |
| `/#projects` | 🚧 Projects |
| `/#technical-profiles` | 💻 Coding, development & community profiles |
| `/#work-experience` | 💼 Internships & experience |
| `/#certifications-detail` | 📜 Certifications |
| `/#achievements` | 🏆 Achievements |
| `/#contact` | 📬 Contact & social links |

## 📁 Repository Structure

```
gssriram/
├── 🚪 index.html                      # Application — markup, styles, and logic
├── 🧯 404.html                        # Custom not‑found page (noindex)
├── 📄 resume.pdf                      # Downloadable resume
├── 🖼️ profile.jpg · og-image.jpg      # Profile photo · 1200×630 social card
├── 🔖 favicon.ico · favicon*.png      # Favicons (+ apple-touch-icon.png)
├── 🗺️ sitemap.xml                     # Sitemap — site and resume
├── 🤖 robots.txt                      # Crawler rules
├── 🧠 llms.txt                        # Machine‑readable summary for AI assistants
├── 🌍 CNAME                           # Custom domain for GitHub Pages
├── ✉️ zoho-domain-verification.html   # Mail domain verification — do not edit
├── 🧾 codolio-sync-log.md             # Audit log — written only by the workflow
└── ⚙️ .github/workflows/
    └── sync-codolio-stats.yml         # Daily statistics synchronization
```

## 🤖 Automated Statistics Synchronization

A scheduled workflow reads the public Codolio profile (`gssriram`) and updates **only four numbers** in the hero tagline. Every other file and every other word on the page is guarded.

### ⏰ Triggers

| Trigger | Detail |
|---|---|
| 🗓️ **Schedule** | Daily at **02:00 IST** (`30 20 * * *` · 20:30 UTC) |
| 🖱️ **Manual** | Actions → *Sync portfolio coding statistics* → **Run workflow** |

Both run identical logic and differ only in the `Trigger` and `Why it ran` log columns. GitHub may start scheduled runs a few minutes late; the log records the actual start time.

### 📐 Synchronized Metrics

| Metric | Derivation | Shown as |
|---|---|---|
| ✅ **Problems solved** | Sum of question counts across all platforms | `2180+` |
| 🏁 **Contests** | Sum of contest lists across all platforms | `100+` |
| 📅 **Active coding days** | Distinct days with a submission on any platform | `210+` |
| 🔥 **Current streak** | Consecutive active days ending today (UTC) or yesterday | `180+` |

Values are rounded **down** to the nearest 10 and compared as *display values* before anything is touched. Wording, order, `+` signs, and all other tagline figures (platform ratings) never change.

### 🚦 Run Outcomes

| Status | Meaning | `index.html` | Run |
|---|---|---|---|
| 🟢 `UPDATED` | A rounded display value changed | Digits updated | ✅ Success |
| ⚪ `NO CHANGES` | No movement | Untouched | ✅ Success |
| 🟡 `CHANGES NOT ENOUGH` | Live values moved, but no rounded value changed | Untouched | ✅ Success |
| 🔴 `FAILED` | Expected fault — source unreachable or unverifiable, tagline not found | Untouched | ❌ Failure |
| 🟣 `UNKNOWN ERROR` | Unexpected exception | Untouched | ❌ Failure |

### 🧾 Audit Log

[`codolio-sync-log.md`](codolio-sync-log.md) is an append‑only table — one row per completed run, failures included:

| Column | Content |
|---|---|
| **Run** | Run number, linked to the Actions run |
| **Time (IST)** | Start time of the run |
| **Trigger** | `SCHEDULED` or `MANUAL` |
| **Why it ran** | Reason for the run |
| **Result** | One of the five statuses |
| **Problems · Contests · Active Days · Streak** | `displayed+ (live value)`, or `—` on failure |
| **Details** | Changed values, or the failure reason |

### 📊 Example Run Output

```
TRIGGER: MANUAL  ·  2026-10-01 09:43 IST

Problems solved ...... 2180+   (live 2187)
Contests ............. 100+    (live 108)
Active coding days ... 210+    (live 214)
Current streak ....... 180+    (live 186)

RESULT: NO CHANGES  →  portfolio untouched · audit row appended
```

### 💬 Commit Conventions

Every run commits the log; `index.html` is included only on `UPDATED`. Commits are authored with the repository owner's GitHub noreply address.

| Status | Commit subject |
|---|---|
| `UPDATED` | `stats: update coding stats — <date>` *(body lists exact changes)* |
| `NO CHANGES` | `log: coding stats unchanged — <date>` |
| `CHANGES NOT ENOUGH` | `log: coding stats moved, displays unchanged — <date>` |
| `FAILED` | `log: coding stats sync failed — <date>` |
| `UNKNOWN ERROR` | `log: coding stats sync error — <date>` |

### 🛡️ Safeguards

| Control | Behavior |
|---|---|
| 🎯 **Write scope** | Only `index.html` (tagline digits, on `UPDATED`) and `codolio-sync-log.md`; the commit step aborts if any other file differs |
| 🔒 **Atomic updates** | Nothing is written to `index.html` until every validation passes; failed runs leave it byte‑for‑byte unchanged |
| ✔️ **Validation** | Aborts on a malformed log, mismatched tagline copies, unexpected API data, or any non‑digit change |
| 🔑 **Permissions** | `contents: write` only · concurrent runs are serialized |
| 🧱 **Runtime** | Pinned `ubuntu-24.04` runner · `actions/checkout@v7` (Node 24) |

## ⚡ Quick Start

```bash
git clone https://github.com/gssriram9050/gssriram.git
cd gssriram

python3 -m http.server 8000      # 🌐 open http://localhost:8000
```

No installation, no dependencies, no build step. The synchronization script is embedded in the workflow; to test it, extract it into a throwaway copy of the repository — it writes to `index.html` and `codolio-sync-log.md` in the working directory.

## 🧰 Operations

| Symptom | Likely cause | Action |
|---|---|---|
| 🔴 Run failed | Source unreachable, unexpected API shape, or tagline mismatch | Read the latest log row and the first step's output |
| 🔴 `FAILED` after editing the tagline | HTML and JavaScript tagline copies differ, or matched wording changed | Restore identical copies using `Problems Solved`, `Active Coding Days`, `Days Current Streak`, `Contests` |
| 🔴 Workflow refuses to run | Log table header removed | Restore the header row in `codolio-sync-log.md` |
| 🟡 Numbers reverted | Auto‑managed values were edited by hand | Don't edit them — the next run overwrites them |

## ✏️ Content Management

Content and theme defaults live in the `defaultConfig` object in `index.html`. Each section is a `<div id="page-<name>" class="page-content">` container, shown by a nav button (`data-page="<name>"`) and the matching `/#<name>` route. When adding or renaming a section, update the navigation, `llms.txt`, and the JSON‑LD `SiteNavigationElement`.

## 🚀 Deployment

Hosted on **GitHub Pages** at [gssriram.live](https://gssriram.live/) (domain defined by `CNAME`). Pushes to the default branch publish automatically, including the workflow's daily commits. `codolio-sync-log.md` is served publicly at `/codolio-sync-log.md`.

## 📌 Project Status

| ✅ Live | Notes |
|---|---|
| Portfolio site | Nine sections, responsive layout, certificate modal |
| SEO & discovery | Open Graph, JSON‑LD, sitemap, robots, `llms.txt` |
| Daily statistics sync | 02:00 IST schedule + manual trigger, audit log, strict guards |

## 🙏 Acknowledgments

☁️ GitHub Pages & Actions · 📊 Codolio · 🎨 Tailwind CSS · 🔣 Lucide · 🧩 Skill Icons · 🏷️ Shields.io

## 📬 Connect

[![Email](https://img.shields.io/badge/Email-gssriram9050%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gssriram9050@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gssriramofficial-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gssriramofficial)
[![GitHub](https://img.shields.io/badge/GitHub-gssriram9050-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gssriram9050)
[![Codolio](https://img.shields.io/badge/Codolio-gssriram-7c3aed?style=for-the-badge)](https://codolio.com/profile/gssriram)

---

<div align="center">⭐ Built for speed, automated for accuracy ⭐</div>
