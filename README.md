# Transformation Workbench

A narrative-led intelligence blueprint that makes a complex multi-initiative transformation landscape legible enough to reason about — by bringing decisions, dependencies, and readiness into one connected view.

**Live site → [abh1nan9an.github.io/transformation-workbench](https://abh1nan9an.github.io/transformation-workbench/)**

---

## What this is

This is a single-page interactive artefact designed to create clearer visibility into what is changing, what is connected, and what needs to be understood next — so the transformation can be reasoned about, sequenced, and prepared for with greater confidence.

## Structure

The workbench is organised into seven narrative layers:

| Layer | Name | Purpose |
|-------|------|---------|
| 1 | **The Challenge** | Frames the transformation complexity — too many initiatives, unknown dependencies, unclear readiness |
| 2 | **The Promise** | Introduces three reasoning lenses: Decision, Dependency, and Readiness |
| 3 | **Reasoning Surfaces** | Six working views that make the promise usable — from dependency matrices to readiness dashboards |
| 4 | **The Intelligence Underneath** | The structured objects and intelligence pipeline that power every surface |
| 5 | **Illustrative Walkthrough** | Shows how Aurora moves through the draft-first, workshop-based process to become structured intelligence |
| 6 | **Persona Journeys** | How different roles (Enterprise Architect, Transformation Lead, etc.) navigate the workbench |
| 7 | **Staged Evolution** | A three-stage roadmap from legibility to foresight |

## Design System

Built on the **Pandora Universal Design System** — Scandinavian minimalism with warm, confident tones:

- **Typography**: Cormorant Garamond (headings) + Source Sans 3 (body)
- **Palette**: Warm charcoal `#2D2926`, powder pink `#E8B4BC`, soft cream `#FAF6F1`
- **Interactions**: Progressive disclosure via slide-in panels, connected highlighting, scroll-based animations

## Technical

- Single `index.html` file — no build step, no dependencies, no framework
- Vanilla HTML, CSS, and JavaScript
- Google Fonts loaded via CDN
- Deployed via GitHub Pages

## Local development

```bash
python3 -m http.server 8080
# Open http://localhost:8080
```
