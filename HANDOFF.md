# Canvas Design Agent Workshop Handoff

This repo contains the portable workshop materials separated from the general `canvas-design-agent` skill development repo.

Copied from local source repo:

- Source repo: `canvas-design-agent`
- Source skill file: `workshop-kit/SKILL.md`
- Source workshop folder: `01_homepage_schedule/`
- Handoff date: 2026-05-28

## What Is Here

### `SKILL.md`

The newest portable Canvas Design Agent skill file. This is intended for copy/paste or upload into chat-based AI tools during the workshop.

The skill transforms plain text, markdown, and structured course content into Canvas LMS-compatible HTML fragments. It includes the element ID library, Canvas-safe constraints, style tags, accessibility expectations, and output requirements.

### `01_homepage_schedule/`

Numbered workshop materials for a fictitious course called:

`Designing AI Agents: They Are Fun! and They Might Eat Us`

The numbered files are meant to show a gradual progression:

- `00-base-course-homepage-schedule.md` - base course content with no style scaffold.
- `01-style-input-homepage-schedule.md` - introduces a single global style choice.
- `02-section-style-homepage-schedule.md` - keeps the base style but changes only two sections: Learning Units and Weekly Schedule.
- `03-editable-data-homepage-schedule.md` - broader element-level experimentation across the full page.

### `01_homepage_schedule/theAnswers/`

Generated backup HTML answers for workshop use.

- `01-style-input-homepage-schedule/` includes generated outputs for all seven style tags.
- `02-section-style-homepage-schedule/` includes the focused section-style answer.
- `03-editable-data-homepage-schedule/` includes the broader S06 editorial answer.

These HTML files are Canvas fragments, not full webpages. They are designed to be pasted into the Canvas Rich Content Editor HTML view.

## Suggested Workshop Flow

1. Start with `SKILL.md` so participants understand the agent instructions and Canvas constraints.
2. Open `01_homepage_schedule/00-base-course-homepage-schedule.md` to show the raw course material.
3. Use `01-style-input-homepage-schedule.md` to demonstrate changing a single global style tag.
4. Use `02-section-style-homepage-schedule.md` to show a smaller controlled change using element IDs for only two sections.
5. Use `03-editable-data-homepage-schedule.md` to demonstrate deeper element-level control across the whole page.
6. Use `theAnswers/` as backup outputs if a live chat tool fails, times out, or produces inconsistent HTML.

## Media Used In The Examples

The course homepage examples use an Internet Archive image:

`https://dn721207.ca.archive.org/0/items/AILS_AC96-0191-4/AC96-0191-4.jpg`

Image metadata noted in the workshop source:

- Publication date: 1996-06-06
- Rights: Public Domain
- Identifier: `AILS_AC96-0191-4`
- Description: Virtual Environment for facial reconstructive surgery, Dr Ross and Rei Cheng wearing 3D glasses while maneuvering the skull and tissue for facial reconstructive surgery.

The generated answers use `E03 Linked Image`, linking to the full image and displaying a cropped landscape version below the course title.

## Maintenance Notes

If the Canvas Design Agent skill changes in the source repo, update this repo's `SKILL.md` from the latest portable workshop version.

If workshop examples are revised, copy the full `01_homepage_schedule/` folder again so markdown prompts and generated answer files stay together.

Before using the materials live, spot-check generated answer files for Canvas-safe output:

- No `<html>`, `<head>`, `<body>`, `<style>`, `<script>`, or SVG.
- Inline styles only.
- No markdown fences in answer HTML.
- Images use absolute URLs and descriptive alt text.
- Generated answer files remain Canvas fragments, not full standalone pages.
