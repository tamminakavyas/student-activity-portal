# CampusConnect — Student Activity Management Portal

A responsive student activity portal demo built with semantic HTML5 and CSS.

## Files
- `index.html` — page structure, metadata, event content and accessible registration form.
- `styles.css` — responsive layout, visual styles and visible keyboard-focus indicators.
- `ACCESSIBILITY-AUDIT.md` — code-review checklist and instructions for a browser-based audit.

## Run locally
Open `index.html` in a browser. No build tools or dependencies are required.

## Registration form note
The form currently demonstrates native HTML validation and submits its values using a GET request to the page fragment. It does not save registrations. Connect the form to a secure backend or approved form service before production use; use POST and server-side validation for real student data.

## Accessibility features
- Semantic landmarks and ordered heading levels.
- Skip link to main content and descriptive navigation label.
- Explicit labels, fieldsets and legends for grouped controls.
- Native keyboard-operable form controls and required-field validation.
- Visible focus indicators, responsive layout and reduced-motion support.
- Meaningful page title, language, viewport and description metadata.

## Git setup
This project was initialized as a Git repository. Example follow-up commits:

```bash
git add index.html styles.css README.md ACCESSIBILITY-AUDIT.md
git commit -m "Build semantic student activity portal"
```
