---
name: portfolio-page-builder
description: Use this skill when building or revising actual HTML/CSS/JS pages for the Maple Bridge portfolio site, especially when translating a rubric-aligned structure into maintainable static pages and shared components.
---

# Portfolio Page Builder

## Purpose
This skill helps Codex implement static portfolio pages with consistent structure, visual hierarchy, responsive behavior, and reusable styles.

## Use this skill when
- creating a new portfolio page
- restructuring an existing page
- building shared navigation and footer
- implementing timelines, cards, callout sections, evidence grids, or comparison blocks
- aligning a page to the established visual system

## Do not use this skill when
- the task is mostly about content strategy
- the task is a research-writing task
- the task is evaluating rubric coverage without code changes

## Implementation defaults
Prefer:
- semantic HTML
- reusable utility and component classes
- lightweight vanilla JS
- accessible markup
- CSS organized by shared patterns

Avoid:
- page-specific hacks
- inline styles unless tiny and justified
- giant monolithic CSS blocks
- animation-heavy interactions
- framework migration

## Shared components to reuse
Build or maintain reusable patterns for:
- page hero
- section header
- metric cards
- persona cards
- timeline
- comparison matrix
- evidence gallery
- feature-to-requirement mapping block
- before-after comparison
- sticky side table of contents
- footer / references block

## Page-building checklist
Before implementation:
1. identify page purpose
2. identify required sections
3. decide whether shared components already exist
4. inspect current styles before adding new ones

After implementation:
1. check heading order
2. check nav highlighting
3. check mobile layout
4. check spacing consistency
5. check placeholder labeling
6. check accessibility basics

## Content safety rule
Do not invent project evidence.
If real content is unavailable:
- add a clearly labeled placeholder,
- preserve structure,
- avoid fictional data.

## Output expectations
When finished, summarize:
- files created or edited
- shared components added
- assumptions made
- remaining TODO evidence placeholders