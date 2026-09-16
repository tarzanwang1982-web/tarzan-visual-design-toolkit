---
name: tarzan-visual-design-toolkit
description: A visual design routing skill that selects the right UI, diagram, icon, typography, hand-drawn, and GitHub presentation resources for the task.
---

# Tarzan Visual Design Toolkit

Use this skill when creating visual systems, web/UI concepts, diagrams, presentation assets, developer documentation, or design-heavy prototypes.

## Core workflow
1. Identify the output: UI, diagram, presentation visual, README, icon system, typography system, or hand-drawn illustration.
2. Define a visual DNA before production: purpose, audience, mood, layout, typography, palette, imagery, density, and emphasis.
3. Route to one or more sub-skills below. Combine them only when each has a clear role.
4. Prefer accessible, editable, reusable output over decorative complexity.
5. Keep visual language consistent across a single project while allowing deliberate variations between sections or series entries.

## Routing
- `skills/shadcn/SKILL.md`: polished React/Tailwind UI composition and component patterns.
- `skills/radix-primitives/SKILL.md`: accessible unstyled interaction primitives and behavior.
- `skills/radix-colors/SKILL.md`: systematic UI color scales and state-aware color decisions.
- `skills/rough/SKILL.md`: hand-drawn, sketch-like SVG/canvas visuals.
- `skills/mermaid/SKILL.md`: flowcharts, sequence diagrams, architecture, timelines, state and relationship diagrams.
- `skills/simple-icons/SKILL.md`: recognizable brand/service icons.
- `skills/fontsource/SKILL.md`: self-hosted/open-source web typography and font selection.
- `skills/github-readme-stats/SKILL.md`: GitHub profile/repository statistics cards.
- `skills/markdown-badges/SKILL.md`: concise technology/status badges for Markdown documentation.

## Combination examples
For a product UI, use shadcn + Radix Primitives + Radix Colors + Fontsource. For an architecture explainer, use Mermaid + Simple Icons. For a friendly hand-sketched explainer, use Rough + Fontsource. For a GitHub project landing README, use Markdown Badges + GitHub Readme Stats + Simple Icons.

## Guardrails
Do not copy third-party examples blindly. Check the upstream project documentation for current APIs, installation commands, licenses, accessibility guidance, and breaking changes. Never claim an upstream library provides a feature unless verified. Preserve brand/icon naming accuracy. For presentation work, treat these libraries as visual resources rather than forcing web-component conventions into slides.