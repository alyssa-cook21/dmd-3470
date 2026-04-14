---
name: final-project-html5-boilerplate
description: "Workspace instructions for the final-project HTML5 Boilerplate site using Bootstrap. Use when editing the final-project/html5-boilerplate_v9.0.1 files."
applyTo:
  - "final-project/html5-boilerplate_v9.0.1/**"
---

This project is built from the HTML5 Boilerplate template and includes Bootstrap via CDN in `final-project/html5-boilerplate_v9.0.1/index.html`.

Use this guidance when working on the final project:

- Keep changes inside `final-project/html5-boilerplate_v9.0.1/` unless the user explicitly asks to modify another folder.
- Preserve the Boilerplate structure:
  - `index.html`
  - `css/style.css`
  - `js/app.js`
  - `webpack.config.dev.js`, `webpack.config.prod.js`, `webpack.common.js`
  - `site.webmanifest`
- Use Bootstrap classes and components for layout and styling when adding new sections or UI elements.
- Keep custom CSS in `final-project/html5-boilerplate_v9.0.1/css/style.css` and avoid inline styles unless specifically requested.
- For local development and build tasks, rely on the existing npm scripts in `final-project/html5-boilerplate_v9.0.1/package.json`:
  - `npm start` → starts webpack dev server
  - `npm run build` → builds the production bundle

If asked to add content, use standard HTML5 structure and semantic markup consistent with the Boilerplate template.
