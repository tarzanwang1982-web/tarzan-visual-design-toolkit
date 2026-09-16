# Tarzan Visual Design Toolkit

A modular Agent Skills toolkit for visual design, UI composition, diagrams, typography, icons, hand-drawn graphics, and GitHub-facing documentation.

## Install

This repository follows the standard Agent Skills layout and can be installed with the open `skills` CLI.

### Codex — recommended global install

```bash
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit -g -a codex
```

This makes the toolkit available across Codex projects. To install into only the current project, omit `-g`:

```bash
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit -a codex
```

### Inspect available skills before installing

```bash
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit --list
```

### Install one focused skill

```bash
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit --skill mermaid -g -a codex
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit --skill rough -g -a codex
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit --skill shadcn -g -a codex
```

### Install all discovered skills non-interactively

```bash
npx skills add tarzanwang1982-web/tarzan-visual-design-toolkit --all
```

### Other supported coding agents

The same repository can be targeted at other Skills-compatible agents by changing the agent flag, for example `-a claude-code` or `-a cursor`. If no agent is specified, the CLI can detect installed agents and prompt for a destination.

### Update later

```bash
npx skills check
npx skills update
```

## Included skills

| Skill | Purpose | Upstream |
|---|---|---|
| tarzan-visual-design-toolkit | Router/orchestrator for the complete toolkit | this repository |
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

The root `SKILL.md` acts as a router. It identifies the visual task and selects one or more focused sub-skills. Each subdirectory is independently discoverable by Skills-compatible tooling.

## Suggested workflow

For broad visual work, install the complete toolkit and let the root skill route the task. Use `--skill <name>` when you want a deliberately narrow capability. A UI task may combine shadcn, Radix Primitives, Radix Colors, and Fontsource; architecture work may combine Mermaid and Simple Icons; GitHub documentation may combine Markdown Badges and GitHub Readme Stats.

## Design philosophy

Start each substantial visual project by defining its visual DNA: audience, purpose, mood, hierarchy, layout, palette, typography, imagery, and emphasis. Maintain that DNA consistently within the project, while allowing a new project or presentation series to establish a different visual language.

## Upstream accuracy

These skills are adapters and workflow guidance, not vendored copies of the upstream libraries. Always check upstream documentation for current APIs, installation commands, licenses, accessibility guidance, and breaking changes.