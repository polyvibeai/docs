# Product — Polyvibe

## Vision

Polyvibe is the Pinterest for generative AI. We start with fashion as the entry point because it is deeply personal, visually driven, and commercially proven — but the platform architecture is designed to expand into any creative category where people want to visualize themselves or their spaces: interior design, beauty, fitness, travel, and beyond.

The product solves a fundamental problem in online shopping and style exploration: **people can't see themselves in clothes before buying or sharing**. Polyvibe makes that instant, personal, and social.

---

## Product Philosophy

**Private → Public Flow**
Users are brought into a private workspace first. They build confidence experimenting with looks without social pressure. Only after they feel good about a look do they have the option to share publicly. This dramatically lowers the barrier to entry and mirrors how people actually think about style.

**AI is the Hero**
The virtual try-on is not a feature buried in settings — it is the entire product experience. Every design decision should reinforce the magic of "I can see myself in this outfit right now."

**Bridging Virtual and Real**
Polyvibe is not just about AI-generated looks. It connects those looks to real purchasable products. The commerce layer is what makes it sustainable; the AI layer is what makes it magical.

---

## App Architecture

The app is divided into two distinct zones:

### Private Workspace (Bottom Nav — Left Side)
These tabs are personal and not visible to the public by default.

| Tab | Purpose |
|---|---|
| **Library** | Browse and discover fashion items, brands, and outfits to try on |
| **Try-On** | The hero feature — generate AI try-on looks using your avatar |
| **Generations** | Gallery of all your generated try-on images, saved privately |

### Public Social (Bottom Nav — Right Side)
These tabs are community-facing and drive discovery and sharing.

| Tab | Purpose |
|---|---|
| **Feed** | Algorithmic and chronological feed of looks shared by the community |
| **Profile** | User's public profile showing their shared posts and style persona |
| **Posts** | Content the user has chosen to share publicly from their Generations |

---

## Core Features

### AI Avatar Creation
- Users upload photos of themselves
- AI generates a personalized avatar that accurately reflects their body, skin tone, hair, and features
- Avatar is the foundation for all try-on generations
- Avatar can be updated or refined over time

### Virtual Try-On
- Users select items from the Library (or input product URLs / images)
- AI renders the user's avatar wearing the selected outfit
- Results are saved to Generations
- Multiple outfit combinations can be tested in a single session
- Try-On is positioned as the hero functionality throughout the entire app experience

### Library / Discovery
- Curated fashion catalog browsable by category, brand, style, or vibe
- Search functionality for specific items or aesthetics
- Integration with affiliate product links
- Users can save items to try later

### Generations Gallery
- Private archive of all try-on results
- Users can star, organize, or delete generations
- Generations can be converted to Posts for public sharing
- High-res export supported

### Social Feed
- Community-driven discovery of shared looks
- Users can like, save, comment on posts
- Posts link back to shoppable affiliate items
- Algorithmic feed surfaces style-matched content

### Public Profile
- Curated grid of shared looks (similar to Instagram grid)
- Style persona / bio
- Follower / following counts
- Link to affiliate products worn in posts

### PRO Subscription (Phase 3+)
- Unlimited generations per month (free tier has a cap)
- Priority processing / faster generation
- Advanced customization options
- Early access to new features and categories

---

## First-Time User Experience (FTUE)

The onboarding flow is critical and must deliver the "wow" moment as fast as possible.

**Proposed FTUE Flow:**
1. Welcome screen — bold "What's your vibe?" headline with cycling sub-headlines
2. Sign up / login (passkey authentication)
3. Avatar creation — guided photo upload with encouragement and clear instructions
4. Avatar preview — user sees their AI avatar for the first time (this is the first magic moment)
5. Curated outfit selection — "Now let's try something on"
6. First try-on generation — user sees themselves wearing an outfit (this is the second and defining magic moment)
7. Save to Generations, optional share prompt
8. Soft introduction to Feed and social features

**Key design principle:** Do not ask users to follow people, fill out profiles, or engage socially until they have experienced the try-on magic at least once.

---

## User Flow Diagram

```
[Landing Page / App Store]
        ↓
[Sign Up / Onboarding]
        ↓
[Avatar Creation] ← First magic moment
        ↓
[Library — Browse Outfits]
        ↓
[Try-On — Generate Look] ← Defining magic moment
        ↓
[Generations — Private Gallery]
        ↓ (optional)
[Post to Feed — Public Sharing]
        ↓
[Community Discovery — Feed / Profile]
        ↓
[Affiliate Commerce — Shop the Look]
```

---

## Key UX Principles

- Try-On must be accessible from anywhere in the app — it is the primary action
- Generation speed is critical — slow results break the magic
- Private workspace should feel like a personal studio, not a shopping cart
- Public feed should feel like a style magazine, not a social media firehose
- Affiliate links should feel like a natural extension of discovery, not an intrusive ad

---

## Category Expansion Roadmap

| Phase | Category | Notes |
|---|---|---|
| 1 | Fashion | MVP — full try-on, social, commerce |
| 2 | Beauty / Makeup | Avatar makeup simulation |
| 3 | Interior Design | Room visualization with AI |
| 4 | Fitness / Activewear | Specific to body transformation visualization |
| Future | Any visual creative category | Platform architecture supports expansion |

---

## Competitive Landscape

| Competitor | Strength | Polyvibe Differentiator |
|---|---|---|
| Pinterest | Discovery | We add AI try-on and personalization |
| Instagram | Social | We add private workspace and commerce intent |
| Amazon | Commerce | We add AI visualization and style discovery |
| Stitch Fix | Personalization | We add user control and social sharing |
| Existing try-on apps | Try-on technology | We add social discovery and community |

Polyvibe's moat is the combination of private AI workspace + public social discovery + affiliate commerce in a single cohesive experience.
