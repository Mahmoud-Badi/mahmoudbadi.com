# Mahmoud Badi — Portfolio

A responsive, static portfolio. No framework or build step required.

## Preview

Run `python3 -m http.server 4173 --directory dist`, then open http://localhost:4173.

## Edit

- `dist/index.html`: content, experience, project cards, contact links
- `dist/style.css`: typography, layout, responsive styles
- `dist/app.js`: project detail dialogs and the terminal playground
- `dist/assets/`: portrait, project screenshot, resume and favicon

Deploy `dist/` with any static hosting provider. The `.openai/hosting.json` manifest connects this checkout to the private Sites preview; it contains no credentials. Domain DNS has not been changed.

## Content provenance

Experience and education come from Mahmoud's supplied resumes. Project details come from those resumes and the public project READMEs. LinkedIn could not be independently read. Sahel is described as a fictional restaurant, and GetDone/ReadStack as learning projects. Barakah and CougarDegree are hackathon projects, with original typographic covers rather than invented product screenshots. GetDone uses its repository screenshot.

## Accessibility

Semantic landmarks, visible keyboard focus, a skip link, native modal focus management, reduced-motion support, and safe text rendering in the terminal. Terminal commands run locally and do not execute a real shell or send visitor input to a service.
