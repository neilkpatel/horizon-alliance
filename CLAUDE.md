# Horizon Alliance Project Context

## Overview
Website for **Horizon Alliance**, Neil's alliance in the mobile game **Last War: Survival Game**. Used for onboarding new members and sharing battle strategies/schedules.

**Purpose:** Alliance resource hub — schedules, strategies, battle info, member onboarding

**Live site:** https://horizonalliance.me

---

## Tech Stack
- Single-page HTML/CSS/JS (no framework)
- Hosted on Vercel (custom domain: horizonalliance.me)
- Git version controlled (GitHub)
- Dark gaming aesthetic (military/tactical vibe)

---

## Key Files
- `index.html` — Main alliance hub / onboarding page
- `desert-storm.html` — Desert Storm battlefield strategy page

---

## Design System
- **Fonts:** Orbitron (headings, branding), Rajdhani (body)
- **Colors:**
  - Background: `#0a0c0f` (dark), `#12161c` (cards)
  - Accent green: `#4ade80` (primary brand color)
  - Accent orange: `#f97316`
  - Accent red: `#ef4444`
  - Accent blue: `#3b82f6`
  - Accent yellow: `#fbbf24`
- **Style:** Subtle grid background, military/tactical UI elements

---

## Content Sections (index.html)
- Alliance onboarding info
- Weekly event schedule
- Arms Race schedule
- Navigation to battle pages

---

## Battle Pages
- `desert-storm.html` — Desert Storm battlefield (orange-tinted theme variant)
- More battle pages may be added as needed

---

## Development History

### Initial Build (Jan 18, 2026)
- Created alliance onboarding site
- Weekly event schedule
- Arms Race schedule

### Updates (Jan 21, 2026)
- Added header credits with styled badges
- Readability improvements and branding updates
- Moved Desert Storm to separate page
- Renamed main page to "Alliance Hub"
- Added "Last War" to alliance tag

---

## Typical Updates
Neil updates this site based on:
- New battles/events
- Strategy changes
- Schedule updates
- New alliance content

---

## Deployment
```bash
cd ~/Desktop/Projects/horizon-alliance
vercel --prod
```

---

## Session Notes
Use this section to capture decisions, context, or notes during work sessions.

### Feb 3, 2026
- Created this CLAUDE.md file for future session continuity
- Hid Desert Storm event (commented out nav link + banner) — event ended
- Added prominent Discord banner at top (link: https://discord.gg/K86wxg6Xq)
- Added target banner: "Main Target: powerstrokeking123"
- Added FAQ section with collapsible items (nav link: #faq)
  - Use this for interesting alliance intel, tips, and updates
- Expanded FAQ with top 10 Last War game tips (heroes, speedups, dailies, etc.)
- Added Lore section (nav link: #lore) with alliance stories:
  - The Betrayal of powerstrokeking123 (he used Horizon to attack WOUT, then left us to face retaliation)
  - The WOUT Adoption Program (adopting players with "GUY" in their name who leave WOUT)
  - The Iron Reign of captpoptart
- Major UI improvements:
  - Dynamic VS Reset Countdown Timer (counts down to 9 PM EST daily)
  - Leadership Card with R5 (captpoptart) and all R4s in styled chips
  - Mobile hamburger menu for small screens
  - Back-to-top button (appears after scrolling)
  - Sunday added to schedule ("Rest & Prep")
  - Enhanced hover effects on Target banner (glow) and Lore cards (page curl)
  - Moved "Website Inspiration: Frau Schmitt" to footer
  - "Lore" nav link styled gold to match section
  - Kept "Website Creator: Ratatatatatatt" in header

---

## Current Leadership
- **R5:** captpoptart
- **R4s:** Yella Yella, Frau Schmitt, Jesslovesdogs, ChiefsFan28, Smilene, BigDan7070, BigDawgKG, DarthMacLean, 379 Guy, aikosan

## Current Targets
- **powerstrokeking123** — Main target (betrayed alliance)

## Key Links
- **Discord:** https://discord.gg/K86wxg6Xq
- **VS Reset:** 9 PM EST daily
