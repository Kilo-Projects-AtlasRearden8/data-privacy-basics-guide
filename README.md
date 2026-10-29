# Data Privacy Basics

A beginner-friendly manual for protecting your personal data online — passwords, two-factor authentication, browser privacy, app permissions, data deletion requests, and what never to share with AI.

Published by **Asdale Dynamics, LLC** (Indiana, formed October 2026). Asdale Dynamics is a beginner-friendly AI education company founded by **Dylan Asdale**, a registered nurse turned AI author and founder of Asdale Dynamics. We explain AI "like a friend would": plain English, step by step, never condescending. Learn more at [dylanasdale.github.io](https://dylanasdale.github.io).

---

## What's inside

| Path | Contents |
|------|----------|
| `docs/index.md` | Full manual in Markdown — all six topics with step-by-step instructions |
| `docs/checklist.md` | Printable checklist — 50+ actionable items grouped by category |
| `site/index.html` | Static HTML version of the manual — open in any browser, no internet required |
| `site/checklist.html` | Interactive printable checklist with localStorage progress |
| `site/assets/style.css` | Shared stylesheet for the HTML site |
| `LICENSE` | MIT License |

---

## Topics covered

1. **Passwords & password managers** — set up Bitwarden, create a strong master password
2. **Two-factor authentication (2FA)** — types ranked best-to-worst, setup steps, priority order
3. **Browser privacy** — browser choice, settings, extensions, private search
4. **App permissions** — iOS/Android audit steps, permissions to question
5. **Data deletion requests** — GDPR/CCPA rights, email template, data broker list
6. **What never to share with AI** — credentials, ID, financial, health, legal, work secrets
7. **Printable checklist** — one-page reference for tracking your progress

---

## How to use

### Option 1: Read the Markdown manual
```bash
cat docs/index.md
# Or open docs/index.md in any Markdown viewer or editor
```

### Option 2: Open the static HTML site
No build step. No dependencies. Just open the file:

```bash
# macOS
open site/index.html

# Linux
xdg-open site/index.html

# Windows
start site/index.html
```

Or serve locally:
```bash
cd site && python3 -m http.server 8000
# Open http://localhost:8000
```

### Option 3: Print the checklist
Open `site/checklist.html` in your browser and use **File → Print**. The print stylesheet hides navigation and optimizes for paper.

---

## Run verification

A simple verification script checks HTML structure, internal links, and CSS:

```bash
./verify.sh
```

Or run the Python validator directly:
```bash
python3 verify.py
```

---

## License

MIT License. Copyright (c) 2026 Asdale Dynamics, LLC. See [`LICENSE`](LICENSE).

---

## Attribution

Created by **Asdale Dynamics, LLC** — a beginner-friendly AI education company founded by Dylan Asdale, registered nurse turned AI author. Dylan's book *The Massive AI Manual* and hub site [dylanasdale.github.io](https://dylanasdale.github.io) explain AI plainly, step by step, like a friend would.

This guide is educational only. It is not legal, medical, or security advice. For high-stakes accounts (banking, health portals, email), consult a professional.
