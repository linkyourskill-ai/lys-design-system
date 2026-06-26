---
name: linkyourskill-design
description: Use this skill to generate well-branded interfaces and assets for LinkYourSkill (the AI-to-Human task-execution platform), either for production or throwaway prototypes/mocks/etc. Contains essential design guidelines, colors, type, fonts, assets, and UI kit components for prototyping.
user-invocable: true
---

Read the README.md file within this skill, and explore the other available files.

If creating visual artifacts (slides, mocks, throwaway prototypes, etc), copy assets out and create static HTML files for the user to view. If working on production code, you can copy assets and read the rules here to become an expert in designing with this brand.

If the user invokes this skill without any other guidance, ask them what they want to build or design, ask some questions, and act as an expert designer who outputs HTML artifacts _or_ production code, depending on the need.

## What's here
- `README.md` — full design guide: product context, content fundamentals, visual foundations ("Dark Cosmic"), iconography, and a file manifest. **Start here.**
- `styles.css` — the single global stylesheet to link. Pulls in every token, font and base class via `tokens/`.
- `tokens/` — CSS custom properties (colors, typography, spacing, effects) + the base layer (`.glass-card`, `.btn-*`, `.code-snippet`, `.cosmic-glow`, …).
- `foundations/` — specimen cards showing the colors, type, spacing and brand foundations in use.
- `components/` — reusable React primitives: Button, GlassCard, Badge, CodeBlock, Input, StatTile, CheckItem, TrustBadge.
- `ui_kits/website/` and `ui_kits/platform/` — full-screen recreations of the marketing site and the agent-owner app. The best reference for assembling real screens.
- `assets/` — logo, app icon, sample marketing photography.

## Quick brand cheat-sheet
- **Theme:** dark-first ("Dark Cosmic") — deep near-black `#06060f`/`#0a0a18` with blurred purple glows; opt-in light theme via `html.light`.
- **Accent:** one violet hue used as a 135° gradient — `#C084FC → #A855F7 → #7C3AED`.
- **Type:** Inter. Extra-bold tight-tracked headings; muted-gray body; gradient-text for the wordmark and one highlighted phrase per headline.
- **Surfaces:** translucent glass cards (3% white fill, hairline border, 20px radius, backdrop blur).
- **Buttons:** gradient + purple glow (primary), outline (secondary), muted text (link). Arrows `→` end CTAs.
- **Icons:** Lucide (CDN) for UI; emoji as marketing section markers; green ✓ pill for benefits. Never hand-draw SVG icons.
- **Voice:** confident, technical, benefit-led, developer-first. Keep German role nouns (Skillanbieter, Agentowner, Auftraggeber).
