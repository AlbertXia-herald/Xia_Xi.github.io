# AGENTS.md

## Project identity
This repository is a static multi-page GitHub Pages portfolio website for the CPT208 Human-Centric Computing Maple Bridge project.

The site is a **process portfolio**, not the final product system itself.
Its purpose is to document research, requirements, ideation, technical implementation, evaluation, reflection, and team contributions in a way that is clear, elegant, and easy to mark.

## Primary goal
When working in this repo, prioritize:
1. coursework alignment,
2. information architecture clarity,
3. consistency with the visual tone of the Maple Bridge system,
4. evidence-driven presentation,
5. maintainable static front-end code.

## Non-goals
- Do not convert this repo into React, Vue, Next.js, or any framework unless explicitly asked.
- Do not add a backend.
- Do not introduce heavy build tooling unless explicitly asked.
- Do not replace the project with a generic commercial portfolio template.

## Design direction
The portfolio should feel like a "design exhibition + evidence archive".
It should visually echo the Maple Bridge system:
- calm cultural tone
- editorial layout
- modular cards
- strong section hierarchy
- subtle heritage-inspired details

But it must remain more documentation-oriented than the system site.

## Required site structure
Keep or evolve the site around these pages unless the user asks otherwise:
- index.html
- research.html
- requirements.html
- ideation.html
- implementation.html
- evaluation.html
- team.html
- references.html

## Required content expectations
The website should help communicate:
- project motivation
- academic and commercial research gap
- personas and stakeholders
- user journey and user requirements
- crazy eights / design alternatives / rationale
- system architecture and feature mapping
- usability testing and iterative refinement
- team contributions
- references and AI disclosure

## Coursework-sensitive rules
This is coursework. Accuracy matters.
- Never fabricate user research, quotes, test results, or academic findings.
- Never invent interview evidence or evaluation numbers.
- If content is missing, create clear placeholders marked TODO rather than fake evidence.
- Preserve the distinction between:
  - confirmed evidence,
  - drafted copy,
  - placeholder content.

## Content style
Use concise, polished, academic-but-readable language.
Avoid generic marketing fluff.
Prefer this pattern:
Finding -> Design response -> Evidence / implication

## Front-end standards
- Use semantic HTML.
- Keep CSS organized and reusable.
- Use vanilla JavaScript unless explicitly asked otherwise.
- Ensure pages are responsive.
- Ensure navigation is consistent across all pages.
- Prefer reusable components and shared classes over page-specific duplication.
- Keep performance lightweight for GitHub Pages.

## Accessibility rules
- Use meaningful heading hierarchy.
- Ensure sufficient color contrast.
- Provide alt text for meaningful images.
- Keep interactive elements keyboard accessible.
- Avoid motion that harms readability.
- Do not hide critical information behind hover-only interactions.

## Navigation rules
- Use a consistent top nav across all pages.
- Highlight the current page.
- Support clear movement between pages.
- For long pages, prefer an in-page table of contents or sticky section nav.

## Visual rules
Prefer:
- soft off-white backgrounds
- dark ink text
- muted red accent
- restrained decorative motifs
- generous whitespace
- grid-based content organization

Avoid:
- neon gradients
- excessive animation
- cluttered hero sections
- inconsistent card styles
- oversized decorative elements that compete with content

## File editing rules
Before major edits:
1. inspect existing structure,
2. preserve useful assets,
3. avoid unnecessary file churn,
4. explain the plan briefly.

When creating new pages or large sections:
- keep shared layout logic centralized,
- avoid copy-pasting the entire nav/footer into many slightly different versions if a shared JS include pattern can help.

## Done means
A task is done only when:
- the requested page or section is implemented,
- the design stays consistent with the repo style,
- the markup is clean,
- navigation works,
- placeholders are clearly marked if evidence is missing,
- the result is reviewable without hidden assumptions.

## Preferred workflow
For non-trivial tasks:
1. inspect
2. plan
3. implement
4. self-review
5. summarize changed files and remaining TODOs

## Review checklist
Before finishing, check:
- Is the content aligned with the coursework rubric?
- Is anything fabricated?
- Is the page hierarchy clear?
- Is the visual language consistent?
- Is the page mobile-friendly?
- Are there obvious accessibility issues?
- Are all links and navigation paths coherent?

## Repo conventions
Suggested shared CSS split:
- base.css for tokens, resets, typography
- components.css for cards, buttons, tags, timeline, callouts
- pages.css for page-level layout
- responsive.css for breakpoints

Suggested JS split:
- main.js for shared bootstrapping
- nav.js for active nav / menu behavior
- interactions.js for accordions, tabs, before-after sliders, section reveal

## If uncertain
Ask for clarification only when the uncertainty blocks correctness.
Otherwise make the smallest reasonable assumption and clearly note it.