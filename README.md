# VoltMind AI

**Industrial EV Supply Chain & Asset Intelligence — Interactive Prototype**

VoltMind AI is a front-end prototype for a B2B SaaS platform built for industrial EV fleet operators — logistics companies, last-mile delivery fleets, and industrial transport businesses. It unifies fleet health, predictive maintenance, procurement decision-making, and raw-material supply chain risk into a single AI-assisted workspace.

This repository contains a single self-contained, dependency-free HTML prototype: a full marketing site, an authentication flow, and an 11-module application shell — all interactive, all running entirely in the browser.

---

Demo Link: "https://bhargavi2048-boop.github.io/Industrial-EV-Supply-Chain-Asset-Intelligence/"
Demo Video: "https://drive.google.com/file/d/1W1LP2zd3HgHvzgF-VIF5a9xIETjNQ04N/view?usp=sharing"

## ✨ Highlights

- **Zero build step** — one HTML file, inline CSS + JS, no framework or bundler required
- **11 fully designed app modules**, from fleet ops to ESG reporting
- **Real client-side interactivity** — live filtering, a battery-degradation simulator, an ROI calculator, working file exports, and a scripted AI chat assistant
- **Custom SVG charting engine** — no external chart library dependency
- **A cohesive dark, glassmorphic design system** applied consistently across every screen

---

## 📦 What's Included

| Area | Description |
|---|---|
| **Landing Page** | Hero, feature grid, how-it-works, testimonials, pricing, FAQ accordion, footer |
| **Authentication** | Login, Signup (with role selection), Forgot Password, OTP verification |
| **Dashboard** | Fleet-wide KPIs, AI insight cards, charging analytics, activity feed, notifications |
| **Fleet Management** | Searchable/filterable vehicle registry with a table ↔ map view toggle |
| **Battery Health** | Live degradation simulator with sliders, gauge, RUL, and AI recommendations |
| **Predictive Maintenance** | Fleet-wide fault forecasting with prioritized AI alerts |
| **Procurement Intelligence** | OEM comparison table + a working ROI calculator |
| **Supply Chain Risk** | Raw-material supplier risk heatmap and delay predictions |
| **Charging Stations** | Station status table and 24-hour load chart |
| **Carbon & Net Zero** | Emissions tracking, CO₂ trajectory, downloadable ESG report |
| **AI Copilot** | Chat-style assistant with suggested prompts and scripted responses |
| **Reports** | Central export hub — every export produces a real downloadable file |
| **Admin Panel** | User table with a working "invite user" flow |

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** — CSS custom properties power the entire design system
- **Vanilla JavaScript** — all view logic, state, and mock data
- **Custom SVG chart engine** — hand-rolled line, bar, and gauge rendering
- **Google Fonts** — Space Grotesk (display), Inter (body), JetBrains Mono (data)
- **No backend, no database, no external JS libraries**

---

## 🚀 Getting Started

No installation, no dependencies, no build process.

```bash
# clone or download the repo, then simply open the file
open voltmind-ai.html
```

Or double-click the file in any modern browser (Chrome, Edge, Firefox, Safari).

---

## 🔍 Project Status

This is a **prototype**, not a production application. It's designed to demonstrate product direction, UX flow, and design language end-to-end.

**Genuinely working:**
- Live search & multi-filter logic (Fleet Management)
- Battery simulator sliders driving real recalculation
- ROI calculator with real (simplified) math
- File exports via `Blob` + `URL.createObjectURL`
- Invite-user flow updating the UI in real time
- FAQ accordion, notification popover, view navigation

**Mocked / illustrative:**
- Authentication (no real credential checks or sessions)
- Role-based access (defined, but not enforced)
- AI Copilot (dictionary lookup, not a real LLM)
- All fleet, supplier, and station data (fixed sample records)
- "PDF/Excel" exports currently output plain text/CSV

---

## 🗺️ Roadmap

- [ ] Migrate to a real frontend framework (React/Vue)
- [ ] Build a backend with authentication and enforced role-based access control
- [ ] Integrate live telematics/IoT data for fleet & battery modules
- [ ] Connect AI Copilot to a real language model
- [ ] Generate true PDF/XLSX exports
- [ ] Add responsive breakpoints and an accessibility pass

---

## 📄 License

Proprietary — for internal review and demonstration purposes.

---

**Author:** Bhargavi N
