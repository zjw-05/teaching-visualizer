# Interactive Electricity Lessons Implementation Plan

> **For agentic workers:** This plan is executed inline in the current repository because the user requested the deliverable directly.

**Goal:** Pair the three junior-high electricity lessons with an offline, clickable interactive page.

**Architecture:** Keep lesson prose in the existing Markdown files and build a dependency-free `index.html` with inline CSS, SVG diagrams, and JavaScript. Each lesson has a prediction, an action or simulation, feedback, and a concluding rule.

**Tech Stack:** Markdown, HTML, CSS, vanilla JavaScript, inline SVG.

## Global Constraints

- Use accurate junior-high physics and explain cause and effect.
- Never instruct students to create a short circuit.
- Determine rheostat resistance from the connected terminals and effective wire length.
- Label the current/resistance visualization as a simplified model.
- Keep the page dependency-free and usable offline.
- Do not add or run tests unless the user asks for testing.

---

### Task 1: Add the interactive lesson page

**Files:** Create `index.html`.

Add topic navigation; a closed/open circuit prediction; series/parallel selection and bulb-disconnection simulation; and a rheostat slider, terminal selection, effective-length diagram, and causal feedback. Include answer details, native keyboard-operable controls, accessible labels, responsive layout, and print styles.

### Task 2: Pair Markdown lesson guides with the interactive page

**Files:** Modify `README.md` and `lessons/01-current.md`, `lessons/02-series-parallel.md`, `lessons/03-rheostat.md`.

Link each guide to the matching interactive lesson and make the prediction/operation/verification steps match the page while preserving hands-on alternatives and safety notes.

### Task 3: Review deliverables

Review the final page and Markdown for completeness, accessibility basics, correct causal explanations, and model limitations. Do not run tests unless requested.
