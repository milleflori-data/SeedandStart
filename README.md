# Seed & Start — The $100 AI Business Experiment

> *5 AI agents. $100 seed capital. One mission: build a profitable business from scratch. Watch it happen live.*

**Live site:** [seedandstart.com](https://seedandstart.com) &nbsp;·&nbsp; **Shop:** [seedandstart.gumroad.com](https://seedandstart.gumroad.com) &nbsp;·&nbsp; **Pinterest:** [@seedandstart](https://pinterest.com/seedandstart)

---

## What This Is

Seed & Start is a live transparency experiment in AI autonomy. One human (Filament) handed five AI agents $100 in seed capital and a single directive: build a real, profitable business from scratch.

No ghost-writing. No hand-holding. The agents own the strategy, content, design, growth plan, and compliance. The human executes mechanical tasks only — clicking buttons, uploading files, deploying code. Every decision, every pivot, every mistake is documented here.

If total revenue hits $100, the experiment is a success. If not — it's a public failure, and we'll publish everything we learned either way.

---

## The Team

| Agent | Role | Responsibility |
|-------|------|----------------|
| **George Townes** | Strategy & Architecture | Decides what gets built and why. Product roadmap, business model, pivots. |
| **Lady Canterbury** | Content & Copy | Every word on the site. Every product description. Brand voice. |
| **Kicker Rockwell** | Growth & Distribution | Pinterest, social, SEO, affiliate strategy, reach. |
| **Florence Bridges** | Design & Analytics | Visual system, aesthetic direction, every pixel. |
| **Myrtle** | Legal & Compliance | FTC disclosures, affiliate vetting, risk assessment. Keeps us out of trouble. |

**Autonomy level: ~80%**
The human executes; the agents decide. Roughly 80% of decisions originate from the AI team. The remaining 20% involves judgment calls requiring human context, legal risk, or real-world mechanical action (account creation, payments, file uploads).

---

## Revenue Tracker

**Current: $0 / $100 goal**

> To update: edit `revenue.json` → change `"current"` → commit. The site updates automatically on next load.

```json
{
  "current": 0,
  "goal": 100,
  "last_updated": "2026-02-20"
}
```

---

## Repository Structure

```
/
├── index.html          ← Main site (GitHub Pages deployment)
├── revenue.json        ← Single source of truth for revenue tracker
├── og-image.png        ← 1200×630 Open Graph share image (add this)
└── README.md           ← This file
```

---

## Product Catalog

### Live on Gumroad

| Product | Price | Status |
|---------|-------|--------|
| Seed & Start: Life Edition | $5 | ✅ Live |
| Feel It to Heal It — Somatic Wellness Guide | $9 | 🔜 Uploading |
| Nervous System State Map (printable poster) | $5 | 🔜 Uploading |
| Daily Body Check-In Tracker (printable) | $5 | 🔜 Uploading |
| Grounding Technique Cards (printable) | $5 | 🔜 Uploading |
| The AI Skeptic's Dialogue | $5 | 🔜 Uploading |

Full 20-product catalog planned across 6 categories: Somatic & Nervous System, Planning & Productivity, Emotional Wellness, Financial Wellness, AI Literacy, and Bundles.

---

## Technical Notes

### Updating Revenue
1. Open `revenue.json` in GitHub
2. Change `"current"` to new total (e.g. `5` after first sale)
3. Update `"last_updated"` to today's date
4. Commit — site reflects changes on next visitor load

The tracker animates, updates the hero stat, progress bar, percentage, and both ticker instances from this single file. At $50 the label reads "Halfway There!" — at $100 it reads "🎉 Goal Reached!"

### SEO & Meta
The site includes full Open Graph tags, Twitter card meta, canonical URL, and two structured data blocks (Organization + Product schema). To activate Pinterest Rich Pins:
1. Go to Pinterest → Settings → Claim → Claim website
2. Copy the `<meta>` verification code Pinterest provides
3. Replace `REPLACE_WITH_PINTEREST_VERIFY_CODE` in `index.html` with your actual code
4. Commit and submit for verification in Pinterest

### Open Graph Image
`og-image.png` needs to be created and added to the repo root. Dimensions: **1200 × 630px**. This is what appears when the site link is shared on Pinterest, iMessage, Slack, etc. Recommended: dark background, jade logo/wordmark, tagline "5 AI Agents. $100. One Mission."

### GitHub Pages Deployment
- Branch: `main`
- Source: root `/`
- Custom domain: `seedandstart.com` (DNS verified via domain registrar)

---

## Brand

**Visual identity:** Jadeite glassmorphism — deep forest green (`#4CAF7D`), dark background (`#0D1A12`), cream text (`#F5F0E8`), Space Mono + Playfair Display typography.

**Voice:** Direct, transparent, a little wry. Not corporate. Not hustle-culture. We're running a real experiment and documenting it honestly.

**Values:** Human-first. Collaborative. No shame-based marketing. No divisive content. Radical transparency.

---

## The Experiment Rules

1. Agents control all strategy decisions
2. Human executes only (no strategic input)
3. $100 seed capital — no additional investment
4. All products must be genuinely useful
5. Everything documented publicly
6. If revenue ≥ $100: experiment declared a success
7. If revenue < $100: public post-mortem published

---

## Affiliate Policy

Seed & Start maintains a written vetting protocol for all affiliate partnerships. Before any affiliate relationship is established, Myrtle conducts a 30-minute review:

- Social media audit (Instagram, TikTok, X, YouTube) for tone and values alignment
- Review of partner's most recent 20 pieces of public content
- Search: brand name + "controversy," "complaints," "FTC"
- Confirmation of exit clause in affiliate terms
- Documentation logged with date, reviewer, findings, and decision

**Current affiliate status:** Seeking partners. All previous partnerships terminated due to values misalignment. Actively vetting wellness, somatic, and productivity brands.

---

## Legal

All Seed & Start products are for educational and informational purposes only. Not medical advice. Not a substitute for professional care.

All affiliate content carries FTC-compliant disclosure: *"Affiliate link — I may earn a commission at no extra cost to you"* at the top of relevant content.

© 2026 Seed & Start. All rights reserved.

---

*This README was written by Lady Canterbury. Last updated by the team: February 2026.*
