# Business — Polyvibe

## Business Model

Polyvibe operates on a dual-revenue model: **affiliate commerce** as the primary revenue stream, and **PRO subscriptions** as the secondary stream. This combination allows the product to be free for most users while monetizing naturally through commerce intent.

---

## Revenue Streams

### 1. Affiliate Commerce (Primary)
- Every product featured in the app carries an affiliate link
- When a user shops a look — whether from their own generation or from the community feed — Polyvibe earns a commission
- Commission rates vary by brand and affiliate network (typically 5–15% per sale in fashion)
- This revenue scales directly with the quality of the try-on experience: better try-ons → more purchase confidence → more conversions
- No inventory, no fulfillment — pure margin business

**Key insight:** The try-on experience is the conversion tool. A user who has "worn" an outfit virtually is dramatically more likely to purchase than one who has only seen a flat product image. This is Polyvibe's core commercial thesis.

#### Affiliate Network Strategy

The approach is layered: one aggregator for broad catalog coverage, then direct network accounts for higher margins on top-performing brands.

**Layer 0 — Aggregator (Integrate First)**

| Network | Role | What It Provides |
|---|---|---|
| [Skimlinks](https://www.skimlinks.com/) | Primary integration | One API → 48,500 merchants across 50+ networks. Product catalog API (~1B products) with pricing, images, and availability. Powers the Library's product data + affiliate monetization in a single integration. |

**Tier 1 — Direct Network Accounts (Add at Launch)**

| Network | Why | Key Fashion Brands | Commission |
|---|---|---|---|
| [Rakuten Advertising](https://rakutenadvertising.com/) | Premium fashion, higher payouts than aggregator pass-through | Sephora, Nordstrom, Macy's, New Balance, Adidas | 5–15% |
| [CJ Affiliate](https://www.cj.com/) | Largest fashion vertical, enterprise-grade tracking | H&M, Puma, Levi's, Express, Revolve | 5–15% |

Direct accounts give higher commission rates than what Skimlinks passes through (Skimlinks takes a margin as the aggregator). For top-performing brands, the direct relationship = more revenue per sale.

**Tier 2 — Post-Launch**

| Network | Why | Notes |
|---|---|---|
| [Impact](https://impact.com/) | Growing fast, strong DTC fashion brands | Nike runs through Impact. Good API and Shopify ecosystem. |
| [Awin](https://www.awin.com/) | EU/UK fashion expansion | Absorbed ShareASale (Jan 2025). Add when entering international markets. |

**Tier 3 — Fallback / Deprioritized**

| Network | Notes |
|---|---|
| Amazon Associates | 1–4% fashion commission (low). PA-API deprecated April 2026, migrating to "Creators API." Cannot use product data directly in mobile apps — must deep-link. Use only as last-resort for items no other retailer carries. |

**Direct Brand Programs:** Most major brands (ASOS, Nike, H&M, Zara, Nordstrom, Revolve, SSENSE) run their affiliate programs through the networks above. Go direct only when negotiating higher rates after proving volume, or for co-marketing deals.

**Implementation sequence:**
1. Pre-launch: Integrate Skimlinks API → populate Library with product catalog + monetized links
2. Launch: Add Rakuten + CJ direct accounts for top brands where commission delta matters
3. Post-PMF: Add Impact (Nike/DTC), Awin (EU). Negotiate direct brand deals for top converters.

### 2. PRO Subscriptions (Secondary)
- Free tier includes limited generations per month (cap TBD)
- PRO tier unlocks:
  - Unlimited generations
  - Faster processing / priority queue
  - Advanced features (multi-item outfits, enhanced customization)
  - Early access to new categories
- Pricing TBD — expected range: $9.99–$19.99/month
- PRO launches in [Phase 3](./ROADMAP.md#phase-3--pro-subscription-launch) after proving engagement and retention with free users

### 3. Future Revenue Opportunities (Not Yet Prioritized)
- Brand partnerships / sponsored content in feed
- White-label try-on technology for fashion retailers
- Creator monetization tools (affiliate revenue sharing with top users)
- Data and trend insights (anonymized, privacy-compliant)

---

## Legal Structure

### Entity
- **Type:** Delaware LLC
- **Formed:** December 2024
- **Members:** Phil Karl (50%) + William Key (50%)
- **Operating Agreement:** In place

### Planned C-Corp Conversion
- The LLC will be converted to a Delaware C-Corporation prior to raising venture capital
- **Reason:** Venture capital firms (especially institutional) require C-Corp structure
- **Tax Strategy:** C-Corp conversion is timed to maximize **Qualified Small Business Stock (QSBS)** benefits under IRC Section 1202
  - QSBS allows founders and early investors to exclude up to $10M (or 10x basis) in capital gains from federal taxes on qualifying stock
  - The 5-year holding period begins at conversion / issuance, so earlier conversion = earlier QSBS eligibility
  - Must remain under $50M in gross assets at time of stock issuance to qualify
- **Advisors:** Professional legal and accounting advisors engaged for entity optimization

### Trademark
- **Filed:** USPTO trademark application submitted
- **Classes:** Multiple classes covering the Polyvibe name and brand
- **Status:** Pending (USPTO review timeline: 8–12 months typically)
- Trademark strategy protects the brand as we scale and as imitators emerge

### Legal Documents
- Operating Agreement (LLC)

---

## Fundraising Strategy

### Current Status
- Bootstrapped / self-funded
- Focused on achieving product-market fit before raising

### Target Raise
- Seed round anticipated after MVP validation and early user traction
- Target investors: AI-focused VCs, consumer app funds, fashion/commerce-adjacent investors — see [COMPETITORS.md — Market Signals](./COMPETITORS.md#market-signals) for competitive funding context
- QSBS-optimized structure will be in place before any institutional round

### Strategic Acquisition Consideration
- The AI market is extremely active with strategic acquisitions
- Polyvibe's combination of proprietary user data, avatar technology, and commerce relationships creates acquisition appeal for:
  - Large fashion retailers (LVMH, Nordstrom, etc.)
  - Social platforms (Pinterest, TikTok, Instagram)
  - AI companies expanding into consumer verticals
  - E-commerce platforms (Shopify, Amazon)
- Building with acquisition optionality in mind without optimizing exclusively for it

---

## Unit Economics (Targets)

| Metric | Target |
|---|---|
| CAC (Customer Acquisition Cost) | < $10 (organic/UGC-driven initially) |
| LTV (Lifetime Value) | To be validated post-launch |
| Free → PRO Conversion | 5–10% target |
| Affiliate Conversion Rate | 2–5% of try-on sessions |
| Monthly Churn (PRO) | < 5% target |

---

## Key Business Risks and Mitigations

| Risk | Mitigation |
|---|---|
| AI generation quality | Continuous model improvement; quality gates before launch |
| Affiliate commission rate compression | Diversify brand partnerships; build direct brand relationships |
| Platform dependency (App Store) | Build web-based version in parallel (custom-built landing page → web app) |
| Copycat competitors | Speed to market, brand building, user data moat, trademark protection — see [COMPETITORS.md](./COMPETITORS.md) |
| Avatar privacy concerns | Clear privacy policy, no data selling, transparent data use |
| Slow user growth | UGC-first marketing, influencer seeding, product virality loops |
