# design-taste-frontend

A Claude Code skill for anti-slop frontend design work — landing pages, portfolios, and redesigns. It reads the brief, infers the right design direction, and ships interfaces that don't look templated. Not intended for dashboards, data tables, or multi-step product UI.

## Install (Claude Code)

```
/plugin marketplace add tenacityinc/design-taste-frontend
/plugin install design-taste-frontend@design-taste-frontend
/reload-plugins
```

The skill then activates automatically on frontend design tasks (landing pages, portfolios, redesigns), or explicitly via the Skill tool.

## What's inside

- `plugins/design-taste-frontend/skills/design-taste-frontend/SKILL.md` — the full skill: brief inference, contextual design-system rules, audit-first redesign flow, and a pre-flight check.

## Updating

Bump `version` in both `.claude-plugin/marketplace.json` and `plugins/design-taste-frontend/.claude-plugin/plugin.json`, push to `main`, then consumers run `/plugin update design-taste-frontend@design-taste-frontend` (or re-run `/reload-plugins`).
