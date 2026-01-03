# .github
Unitymbed Organization 
# unitymbed.com — Official Website Documentation KhaoYai-Edition.
Version 1.0  
Maintainer: Jesada Pholcharoen (UnityMbed / Teva)  
Last updated: 2026-01-03

---

## 1) What is unitymbed.com?
**unitymbed.com** is the official public-facing website of the **UnityMbed** organization.  
Its purpose is to serve as the **single source of truth** for the UnityMbed ecosystem: platform overview, documentation entry points, downloads/releases, EDU onboarding, and commercial contact.

UnityMbed is an AI-assisted embedded development ecosystem that combines:
- **UnityCore DevKits** (Cortex-M MCU boards)
- **Open toolchain workflows** (GCC + OpenOCD/Probe)
- **Teva Flash/Debug tools** (cross-platform)
- **Policy-aware AI assistance** (to accelerate learning & development)
- **Education-ready materials** (labs, examples, course packs)

The website is the “front door” for users, schools, and partners to understand the system quickly and reach the right resources.

---

## 2) Target audiences (who the website is for)
unitymbed.com is designed for multiple groups, with a clear “path” for each:

### A) Students & Makers
- Quick start learning path
- Examples that work out-of-the-box
- Simple flashing/debugging steps
- Beginner-friendly docs and lab modules

### B) Engineers & Researchers
- SDK / HAL reference
- Toolchain setup guides
- Board pinouts, schematics references
- Advanced examples (CAN, motor control, power electronics, BMS)

### C) EDU Institutes (universities, training centers)
- Seat-based licensing overview
- Onboarding steps (50-seat or more)
- Curriculum packs, lab material
- Instructor guides and deployment checklist

### D) Enterprise / OEM Partners
- Commercial licensing contact
- Integration & policy requirements
- Security posture (no direct key exposure, serverless gateways)
- Custom build / support / SLA (if applicable)

---

## 3) What the website should contain (recommended sections)
Below is the recommended “standard structure” for unitymbed.com.

### 3.1 Home / Landing
**Goal:** explain UnityMbed in 10 seconds.
- One-line value proposition
- What it includes (DevKit + Toolchain + Flash/Debug + AI)
- Who it is for (EDU → Industry)
- Call-to-action buttons: **Get Started**, **Docs**, **Downloads**, **For EDU**, **Contact**

### 3.2 Product / Platform Overview
**Goal:** show the ecosystem clearly.
- UnityCore DevKits (supported MCU series)
- Teva Flash Tool (workflow, supported probes)
- SDK / examples
- AI assistance (what it does / what it does NOT do)

### 3.3 Documentation Hub (Docs)
**Goal:** route users to correct docs instantly.
- Getting started (5–10 minutes)
- Toolchain setup (Windows/macOS/Linux)
- Flashing/debugging guide
- Examples & tutorials
- FAQ & troubleshooting

### 3.4 Downloads / Releases
**Goal:** make it easy to install and start.
- Latest releases (Flash tool, SDK packages)
- Driver/probe references
- Release notes & change log

### 3.5 EDU Page (For Institutes)
**Goal:** convert institutions.
- EDU plan overview (seats, duration)
- What they get (labs, materials, onboarding)
- Steps to onboard: domain list / seat provisioning / instructor pack
- Contact button for quotation

### 3.6 Community / Updates
**Goal:** show activity and trust.
- News/updates
- Workshop schedule
- Community links (Discord/Facebook/YouTube/GitHub)

### 3.7 Contact / Partnership
**Goal:** close collaboration.
- EDU partnership
- Distributor inquiry
- Enterprise/OEM inquiry
- Contact form + email + company/maintainer identity

---

## 4) Key message (copy that should appear in multiple places)
Use this message consistently across homepage, docs, and GitHub:

> **UnityMbed is an AI-assisted embedded ecosystem: hardware DevKits + open toolchain + Teva Flash/Debug, designed for education and scalable to real engineering teams.**

And an important boundary statement:

> **AI and simulation outputs are advisory and must be verified by engineers before real-world deployment.**

---

## 5) Licensing & policy statement (website-ready)
UnityMbed should present licensing in a clean and credible way:

### Dual-License Policy
- **Free for Education & Research (Non-Commercial):** learning, training, labs, academic use  
- **Commercial / Production:** requires a paid license or signed agreement

### Trademark / Third-party notice (short)
- Arm®, Cortex® are trademarks of Arm Limited. UnityMbed is not affiliated with or endorsed by Arm.
- Third-party tools/libraries remain under their original licenses.

> Tip: Put “Licensing” in footer and link to the full `LICENSE.md` in GitHub.

---

## 6) Website ↔ GitHub relationship (how unitymbed.com should connect)
The website should act as a navigation layer and credibility layer, while GitHub hosts the technical artifacts.

### Recommended GitHub repos (linked from the website)
- `unitymbed-core` — SDK / HAL / drivers
- `unitymbed-flash` — Teva Flash CLI/GUI + configs
- `unitycore-devkit` — hardware docs (schematics, BOM, pinout)
- `unitymbed-examples` — labs & examples
- `docs` — documentation source (if docs are in GitHub)

### Website should link to
- Releases page (download)
- Docs pages
- Example repository
- Issue tracker (bug reports)
- Roadmap (optional)

---

## 7) Standard user journey (what a visitor should do)
### Journey 1: New learner
Home → Get Started → Install toolchain → Flash example → Learn modules

### Journey 2: Engineer evaluating
Home → Platform overview → Docs → Examples → Release notes → Contact

### Journey 3: EDU institute
Home → For EDU → Plan/Seats → Onboarding checklist → Quotation → Provision seats

### Journey 4: Enterprise/OEM
Home → Enterprise/Partner → Policy/Security → Licensing → Contact

---

## 8) Quality standards (what “production-ready website” means)
A production-ready unitymbed.com should meet these:
- Fast loading (high Lighthouse scores)
- Clear navigation to docs/downloads
- Mobile-friendly
- No broken links
- Versioned releases (downloads correspond to GitHub releases)
- Transparent licensing & policy statement
- Contact path that actually converts (simple form, fast reply)

---

## 9) Deployment & maintenance (recommended)
### Deployment approach (choose one)
- Netlify (simple static hosting + previews)
- Vercel (great for Next.js)
- GitHub Pages (simple, but fewer advanced features)

### Maintenance rules
- Every release should update:
  - download links
  - release notes
  - compatibility notes (boards/tools)
- Keep “Get Started” always current with latest stable release

---

## 10) Suggested footer text (website)
**UnityMbed / Teva**  
AI-Powered Embedded Platform — DevKit + Toolchain + Flash/Debug  
Dual-license: Free for EDU/Research; Commercial license required for production  
Arm®, Cortex® are trademarks of Arm Limited. Not endorsed by Arm.  
GitHub: https://github.com/Unitymbed

---

## 11) Checklist (ready-to-publish)
- [ ] Homepage with clear value proposition + CTAs
- [ ] Docs hub with quickstart
- [ ] Downloads page linked to GitHub Releases
- [ ] EDU onboarding page with seat-based plan
- [ ] Licensing page (dual-license + notices)
- [ ] Contact page/form
- [ ] Community links
- [ ] No broken links + mobile responsive
- [ ] Basic analytics (optional)

---

END
