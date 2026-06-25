# Hermes Hackathon Intel

Competitive intelligence dashboard for the **Nous Research Hermes Agent hackathons** — business and creative tracks.

Every submission scraped from Discord with:
- Plain-language AI summaries and step-by-step flow breakdowns
- Usefulness / Viability / Presentation scores (1–10 each, max 30)
- Embedded demo videos (YouTube, Twitter, MP4)
- Traction metrics (Discord reactions + comments + X reach)
- Full author writeups, expandable per row

## Tracks covered

| Track | Submissions | Prize pool |
|-------|------------|------------|
| Accelerated Business (current) | 38 | — |
| Creative (previous, winners highlighted) | 220 | $26k |

## Tech

Single self-contained `index.html` — no build step, no dependencies, no server needed. Open locally or deploy anywhere static.

## Updating

A daily routine checks `#hermes-accelerated-business-hackathon` on the Nous Research Discord for new submissions and patches `index.html` automatically.

## Scoring methodology

Scores are analytical estimates for competitive research — not the official judges' scores.

- **Usefulness** — how real and impactful the business problem is
- **Viability** — completeness: live site, real-money demo, working code, guardrails vs. concept-only
- **Presentation** — clarity of writeup + demo polish

Traction (Discord reactions/comments, X views) is shown as a secondary signal.
