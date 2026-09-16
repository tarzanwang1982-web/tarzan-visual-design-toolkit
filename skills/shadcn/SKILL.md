---
name: shadcn
description: Build polished, accessible component-based React interfaces using shadcn/ui patterns and the current upstream shadcn skill as the authoritative reference.
---
# shadcn/ui
Use for application UI, dashboards, forms, navigation, overlays, data display, settings pages, chat interfaces, and reusable design systems when styled source components are preferable.

Official upstream skill: https://github.com/shadcn-ui/ui/tree/main/skills/shadcn
Upstream project: https://github.com/shadcn-ui/ui

## Core principles
- Inspect the target project's existing components and configuration before adding or changing components.
- Prefer existing shadcn components and composition over hand-rolled equivalents.
- Use semantic design tokens rather than arbitrary raw colors.
- Preserve accessibility requirements for dialogs, forms, menus, focus, labels, and interactive states.
- Compose complete component structures rather than visually similar incomplete markup.
- Use the project's actual package manager, aliases, icon library, framework conventions, and primitive base.
- Before implementation, consult the current official shadcn skill/docs because its CLI and component guidance evolve.

## Toolkit routing
Combine with Radix Primitives when low-level interaction behavior needs special attention, Radix Colors for systematic palettes, Fontsource for typography, and Simple Icons when recognizable brand/service marks are needed.