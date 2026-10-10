# Kontur: SaaS Landing Page Prototype

Annotated, clickable prototype for a fictional workflow-automation product ("Kontur").
Language: German. Single self-contained file, no dependencies except Google Fonts.

## Run it

Open `index.html` in a browser. Nothing to install or build.

## What's inside

| # | Component | States documented |
|---|---|---|
| 1 | Hero CTA (primary button) | default, hover, active, focus |
| 2 | Feature card | default, hover, active |
| 3 | Pricing toggle (monthly/yearly) | monthly, hover, yearly |
| 4 | Testimonial slider | default, slide change, arrow hover |
| 5 | Lead form field and submit | default, hover, focus, error, loading, success |

Each section has a spec table with trigger, visual change, duration and easing.
The page ends with the global transition rules (design tokens).

## Design decisions

- **Timing:** 150–200 ms for micro-interactions, 300 ms for standard state changes,
  300–500 ms for panel changes. All use ease-out.
- **Feedback:** errors combine an immediate border color change with a single 400 ms shake.
- **Accessibility:** visible focus rings, `role="switch"` with `aria-checked` on the toggle, labelled form fields, and `prefers-reduced-motion` support.

## Note

All content is for demonstration only.
