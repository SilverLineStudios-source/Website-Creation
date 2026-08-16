# Website-Creation

## UI/UX Pro Max skill

This repo includes the [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) design
skill under `.claude/skills/`. It gives Claude searchable local databases of UI styles, color
palettes, font pairings, UX guidelines, and stack-specific implementation guidance (React, Next.js,
Vue, Tailwind, shadcn/ui, and more), and is loaded automatically in any Claude Code session opened in
this project.

Included skill bundles:
- `ui-ux-pro-max` — styles, palettes, typography, UX guidelines, charts, stack guidance
- `ui-styling` — Tailwind/shadcn theming helpers and canvas fonts
- `design-system` — design tokens and slide/token tooling
- `design` — logo, icon, banner, and CIP asset guidance
- `brand` — brand guideline and consistency tooling
- `banner-design`, `slides` — supporting reference material

Source: https://github.com/nextlevelbuilder/ui-ux-pro-max-skill (MIT licensed, see `.claude-plugin/LICENSE`).

## shadcn/ui skills

Also included: [mattbx/shadcn-skills](https://github.com/mattbx/shadcn-skills), two skills for working
with shadcn/ui components:
- `shadcn-component-discovery` — searches shadcn-compatible registries (Magic UI, Aceternity, ReUI,
  Animate UI, DiceUI, Tailark, AI Elements, etc.) for existing components before building custom UI
- `shadcn-component-review` — reviews components against shadcn design patterns and theme styles
  (Vega, Nova, Maia, Lyra, Mira)

Source: https://github.com/mattbx/shadcn-skills (license in `.claude-plugin/third-party/shadcn-skills-LICENSE`).

## Design style skills

Also included: [bergside/awesome-design-skills](https://github.com/bergside/awesome-design-skills), a
registry of 67 self-contained visual-direction skills (one per named style, e.g. `glassmorphism`,
`brutalism`, `neumorphism`, `minimal`, `material`, `retro`, `vibrant`, `enterprise`, `editorial`, and
many more). Each gives typography scale, color tokens, spacing, component rules, accessibility
requirements, and do/don't guidance for that specific style — use one when the project needs a
particular visual direction.

Source: https://github.com/bergside/awesome-design-skills (license in
`.claude-plugin/third-party/awesome-design-skills-LICENSE`).

## GSAP animation skills

Also included: [greensock/gsap-skills](https://github.com/greensock/gsap-skills), the official GreenSock
skills for the GSAP animation library:
- `gsap-core` — core tween API (`gsap.to/from/fromTo`, easing, duration, stagger, `matchMedia`)
- `gsap-timeline` — sequencing multiple animation steps
- `gsap-scrolltrigger` — scroll-linked animation
- `gsap-react` — React-specific usage (`useGSAP`, refs, cleanup)
- `gsap-frameworks` — Vue/Svelte/Nuxt/vanilla usage patterns
- `gsap-plugins` — Flip, Draggable, and other GSAP plugins
- `gsap-utils` — helper functions (clamp, mapRange, etc.)
- `gsap-performance` — animation performance guidance

Source: https://github.com/greensock/gsap-skills (license in `.claude-plugin/third-party/gsap-skills-LICENSE`).

## Power Design (brand-native generator)

Also included: [ItsssssJack/power-design](https://github.com/ItsssssJack/power-design) (`power-design`),
which generates on-brand HTML decks or full responsive websites by combining brand DNA (colors, fonts,
logo, voice — extracted via Firecrawl from a URL, or picked from 70+ pre-built brand profiles under
`brands/`) with two codified rulebooks:
- `principles/design-principles.md` — 20 non-negotiable rules for slide decks
- `principles/web-principles.md` — 20 non-negotiable rules for responsive websites

Note: pulling brand DNA from a live URL requires the Firecrawl MCP server; the pre-built brand library
and default house style work without it. The upstream repo's illustrative rule images and email assets
were left out here since they're not read by the skill itself.

Source: https://github.com/ItsssssJack/power-design (license in `.claude-plugin/third-party/power-design-LICENSE`).
