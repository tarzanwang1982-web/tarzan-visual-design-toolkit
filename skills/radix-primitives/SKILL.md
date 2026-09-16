---
name: radix-primitives
description: Design accessible React interactions using Radix UI Primitives as low-level, unstyled building blocks.
---
# Radix UI Primitives
Use when behavior, accessibility, focus management, keyboard interaction, layering, dialogs, menus, popovers, tabs, tooltips, selects, or other interactive primitives matter more than prebuilt styling.

Upstream: https://github.com/radix-ui/primitives

## Rules
- Accessibility and interaction semantics come first.
- Treat primitives as behavior foundations; styling belongs to the project's visual system.
- Prefer composition over unnecessary wrappers.
- Verify current component APIs and installation instructions upstream before implementation.
- Test keyboard navigation, focus states, disabled states, open/closed states, and screen-reader semantics.

## Routing
Use shadcn when a higher-level styled component solution is desired. Combine with Radix Colors for coherent states and contrast.