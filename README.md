# Tarzan Visual Design Toolkit

A modular Agent Skills toolkit for visual design, UI composition, diagrams, typography, icons, hand-drawn graphics, and GitHub-facing documentation.

## Included skills

| Skill | Purpose | Upstream |
|---|---|---|
| shadcn | Accessible, component-based application UI | shadcn-ui/ui |
| radix-primitives | Accessible low-level interaction primitives | radix-ui/primitives |
| radix-colors | Systematic UI color scales | radix-ui/colors |
| rough | Hand-drawn SVG/canvas visual language | rough-stuff/rough |
| mermaid | Text-defined diagrams and architecture visuals | mermaid-js/mermaid |
| simple-icons | Brand and technology icons | simple-icons/simple-icons |
| fontsource | Open-source/self-hosted typography | fontsource/fontsource |
| github-readme-stats | GitHub statistics cards | anuraghazra/github-readme-stats |
| markdown-badges | Markdown technology/status badges | Ileriayo/markdown-badges |

## Structure

```text
SKILL.md
skills/
  shadcn/SKILL.md
  radix-primitives/SKILL.md
  radix-colors/SKILL.md
  rough/SKILL.md
  mermaid/SKILL.md
  simple-icons/SKILL.md
  fontsource/SKILL.md
  github-readme-stats/SKILL.md
  markdown-badges/SKILL.md
```

The root `SKILL.md` acts as a router. It first identifies the visual task and then selects one or more focused sub-skills.

## Design philosophy

Start each substantial visual project by defining its visual DNA: audience, purpose, mood, hierarchy, layout, palette, typography, imagery, and emphasis. Maintain that DNA consistently within the project, while allowing a new project or presentation series to establish a different visual language.

## Upstream accuracy

These skills are adapters and workflow guidance, not vendored copies of the upstream libraries. Always check upstream documentation for current APIs, installation commands, licenses, accessibility guidance, and breaking changes.