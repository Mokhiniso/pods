# Pods — Investment Pods MVP

> *Investing isn't scary. Doing it alone is.*

A behavioral fintech landing page and interactive MVP for **Investment Pods** — a platform designed to convert cautious savers into confident investors through collaborative, social investing.

Live site → **[mokhiniso.github.io/pods](https://mokhiniso.github.io/pods)**

---

## What is Investment Pods?

Most people save money but never invest it. Not because they're uninformed — but because investing feels lonely, risky, and complex.

Investment Pods solves this by making investing a **group decision**. Users join small pods of 3–6 people, contribute modest amounts monthly, and vote on investment themes together. Shared decisions mean shared confidence.

The platform is built on three behavioral principles:

- **Reduce perceived risk** — small contributions, no leverage, simple instruments
- **Remove isolation** — every decision is collective, not individual
- **Create progression** — top-performing pods can attract external capital backing

---

## What's in this repo

This is a single-file HTML MVP — no frameworks, no dependencies, no build step.

```
index.html   ← entire landing page + shadow investing flow
```

### Features included in the MVP

- **Dual-tone design system** — warm "savings" mode vs. growth "pod" mode, reflecting the psychological contrast between inaction and investing
- **Live purchasing power calculator** — uses real Eurozone HICP inflation data (2.5%, Eurostat March 2026) to show what savings actually lose over time
- **Pod comparison widget** — side-by-side view of savings erosion vs. pod growth based on S&P 500 historical average (~10%/yr)
- **Shadow investing flow** — a full 4-step simulated experience: pick an interest, set a contribution, vote in a pod, see your result. No real money. Designed to let hesitant users feel the platform before committing
- **Waitlist CTA** — email capture (UI only, not yet wired to a backend)
- **Live pod previews** — simulated active pods showing members, votes, and performance

---

## The psychology behind the design

This isn't just a landing page — every element is intentional:

| Element | Behavioral principle |
|---|---|
| "Doing it alone is scary" headline | Social identity framing |
| Shadow investing flow | Commitment device — experienced users convert faster |
| Vote screen ("your vote decides the outcome") | Agency + consequence without real risk |
| Amount nudges ("most common", "a coffee a week") | Social norming + loss aversion reframing |
| Purchasing power language | Concrete loss over abstract percentage |
| "89% joined a real pod within 2 weeks" | Social proof at the threshold of action |
| Dual-tone color system | Visual reinforcement of the inaction vs. growth contrast |

---

## Roadmap

This MVP demonstrates the concept. A full product would include:

- [ ] Real user authentication and pod creation
- [ ] Backend for waitlist email collection
- [ ] Real brokerage API integration (e.g. Alpaca, Interactive Brokers)
- [ ] Mentor matching and performance-linked incentive system
- [ ] Pod performance tracking and investor discovery layer
- [ ] Country-specific inflation rates (Latvia, Lithuania, Estonia etc.)
- [ ] Mobile app (React Native)

---

## Built with

- Vanilla HTML, CSS, JavaScript — no frameworks
- Real inflation data: [Eurostat HICP March 2026](https://ec.europa.eu/eurostat/web/products-euro-indicators/w/2-31032026-ap)
- Hosted on GitHub Pages

---

## About

Built by **Mokhiniso** as a concept MVP for a behavioral fintech platform targeting the gap between saving and investing in Europe.

Interested in the idea? Have feedback? Open an issue or reach out.
