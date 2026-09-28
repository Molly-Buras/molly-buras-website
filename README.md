# ISDS 4125: Individual Vibe Coding Exercise — Personal Portfolio

**Student:** Molly Buras  
**Course:** ISDS 4125: Analysis and Design of Information Systems  
**Institution:** Louisiana State University (E. J. Ourso College of Business)  
**Live Website:** [https://mollys-making-it.com/molly-buras-website/](https://mollys-making-it.com/molly-buras-website/)  
*(Alternate GitHub Pages link: [https://molly-buras.github.io/molly-buras-website/](https://molly-buras.github.io/molly-buras-website/))*  
**Repository:** [https://github.com/Molly-Buras/molly-buras-website](https://github.com/Molly-Buras/molly-buras-website)

---

## Project Overview

This repository contains my personal professional portfolio website developed as part of the ISDS 4125 Individual Vibe Coding Exercise. The website showcases my background as an Information Systems undergraduate senior at LSU, emphasizing my academic foundation, technical and interpersonal competencies, work history, and career ambitions.

The portfolio is structured across three core pages:
- **Home (`index.html`):** Introduction, professional summary, quick navigation, key skills breakdown, and direct contact details.
- **Resume (`resume.html`):** Structured overview of education, relevant coursework, technical proficiencies, professional work experience, and leadership activities.
- **My Professional Journey (`project.html`):** An in-depth narrative detailing my academic growth in Information Systems, applied project experiences, and long-term career goals.

---

## Development & Tooling

This website was built using **Google Antigravity**, utilizing an agentic "vibe coding" workflow. Instead of manually writing every element line-by-line from scratch, I directed the Google Antigravity agent using iterative natural language instructions to architect the semantic structure, craft a unified styling system, and implement responsive multi-page layouts.

### Technologies Used
- **Semantic HTML5:** Accessible document outlining (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) with ARIA attributes.
- **Vanilla CSS3:** Custom responsive layout system leveraging CSS Grid, Flexbox, custom properties (CSS variables), and media queries without external utility frameworks.
- **Google Antigravity:** Agentic AI coding environment used to scaffold, edit, review, and iterate on code.
- **Git & GitHub Pages:** Version control and static hosting with custom domain integration.

---

## Reflection: Directing the Agent

During this vibe coding exercise with Google Antigravity, a key technical lesson I learned was the critical importance of **modular scoping and CSS cascade management when directing an AI coding agent**.

In early iterations, requesting broad visual updates (such as "improve the layout and polish the design") occasionally produced unintended side effects in `styles.css`—such as overwriting shared layout rules or causing spacing regressions on secondary pages like `resume.html` and `project.html`. 

To direct the agent effectively, I learned to adopt a more disciplined, technical prompting strategy:
1. **Target Specific Components:** Scoping instructions to isolated selector blocks (e.g., `.hero-avatar-frame`, `.skills-grid`, `.timeline-item`) rather than allowing broad document-wide restyling.
2. **Explicit Structural Boundaries:** Specifying exact responsive constraints (such as `max-width`, aspect ratios, and `object-fit: cover` for image assets) to ensure media rendered cleanly across mobile and desktop breakpoints.
3. **Preserving Design Tokens:** Directing the agent to reuse existing CSS custom properties for typography and palette consistency instead of generating arbitrary inline or ad-hoc color values.

This shift in approach demonstrated that successful "vibe coding" is not about vague delegation, but about acting as an informed technical director—guiding the AI with clear architectural constraints, validating changes iteratively, and maintaining control over the codebase's integrity.
