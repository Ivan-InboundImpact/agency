# About Page — Content & Structure Specification

**Project:** Inbound Impact Website
**Page:** `/about`
**Last Updated:** March 2026

---

## Page Overview

The About page establishes Inbound Impact's positioning as a boutique, founder-led HubSpot consulting agency. It communicates credibility through verified metrics, a clear origin story, and well-defined values that differentiate the agency from larger, template-driven competitors.

**Primary objectives:**
- Build trust and authority with prospective clients
- Differentiate from high-volume HubSpot agencies
- Communicate depth of expertise across the full HubSpot ecosystem
- Drive qualified leads toward the contact page

---

## Section 1 — Hero

| Element       | Content                                                                                              |
|---------------|------------------------------------------------------------------------------------------------------|
| **Badge**     | `About us`                                                                                           |
| **Headline**  | Boutique HubSpot consulting                                                                          |
| **Subtext**   | A small, focused team with deep HubSpot expertise. We keep things lean so every client gets our full attention. |

**Design notes:** Full-width hero with subtle gradient orbs and noise texture. Text is left-aligned on desktop, stacked on mobile.

---

## Section 2 — Our Story

### Left Column (Text)

| Element        | Content                                                        |
|----------------|----------------------------------------------------------------|
| **Badge**      | `Our Story`                                                    |
| **Heading**    | Meaningful growth, not just more traffic                       |

**Paragraph 1 (Belief statement):**
> Built on one simple belief — HubSpot should work for you, not against you.

**Paragraph 2 (Origin & positioning):**
> Inbound Impact started from a frustration with how HubSpot projects were typically delivered — bloated retainers, templated solutions. We do it differently. We're a boutique agency specialising exclusively in HubSpot — onboarding and implementation, custom website development, and on-page SEO. Every project is handled by founders & experts who've worked across the full HubSpot stack, from Marketing and Sales Hub to Service and Operations, across Pro and Enterprise tiers.

### Right Column (Stats Grid — 2x2)

| Metric | Value  | Label                   |
|--------|--------|-------------------------|
| 1      | 100+   | HubSpot Portals Set Up  |
| 2      | 30+    | Websites Delivered      |
| 3      | 20+    | Sites Optimised         |
| 4      | 95+    | Avg. PageSpeed Score    |

**Design notes:** Stats use animated count-up on scroll entry. Cards have glassmorphic borders with theme-aware backgrounds.

---

## Section 3 — Our Values

| Element       | Content                                                  |
|---------------|----------------------------------------------------------|
| **Badge**     | `Our Values`                                             |
| **Heading**   | What drives us                                           |
| **Subtext**   | Our core values shape every project and every interaction. |

### Value Cards (4-column grid on desktop)

| #  | Icon     | Title                   | Description                                                                                                                                                 |
|----|----------|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Users    | Boutique by choice      | We deliberately stay small. That means every client works directly with the people actually doing the work — and gets the quality that comes with it.        |
| 2  | Zap      | Custom, always          | We don't use templates — on websites or in HubSpot. Everything is built specifically for your business, so you own it fully and it fits exactly how you operate. |
| 3  | Target   | Technical depth         | We've worked across every Hub, every complexity level, Pro to Enterprise. When something needs to be built properly, we know how to do it.                   |
| 4  | Heart    | Straight communication  | We tell you what's realistic, what's not, and what we'd actually recommend. No overselling, no scope creep surprises.                                        |

**Design notes:** Cards use staggered scroll-reveal animations. Each card has an icon container that transitions from outlined orange to filled orange on hover, with a soft glow effect.

---

## Section 4 — CTA Banner

| Element         | Content                                                                                        |
|-----------------|------------------------------------------------------------------------------------------------|
| **Heading**     | Let's build something **great** together                                                       |
| **Description** | Whether you need a new website, CRM setup, or SEO optimization — we're here to help your business grow. |
| **Button**      | `Start a conversation` → links to `/contact`                                                   |

---

## Design System Notes

- **Typography:** Manrope (headings), Geist Sans (body)
- **Brand colours:** Orange `#FF6600` (primary), Yellow gradient accent
- **Theme support:** Full light/dark mode with CSS custom properties
- **Animations:** GSAP-powered scroll reveals, staggered card entrances, count-up numbers
- **Responsive:** Mobile-first, single column < 768px, multi-column grid on desktop

---

## SEO Metadata

| Property        | Value                                                                                              |
|-----------------|----------------------------------------------------------------------------------------------------|
| **Title**       | About Us \| Inbound Impact                                                                        |
| **Description** | Boutique HubSpot consulting — a small, focused team with deep expertise across all Hubs, Pro to Enterprise. |
| **OG Title**    | About Us \| Inbound Impact                                                                        |
| **OG Description** | Boutique HubSpot consulting — a small, focused team with deep expertise across all Hubs, Pro to Enterprise. |
