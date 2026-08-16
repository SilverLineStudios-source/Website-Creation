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
