# Cessil Tribblet Professional Portfolio

A dependency-free, recruiter-focused static portfolio for Cessil Tribblet.

## Branch safety

- `main` remains the published GitHub Pages site.
- Redesign work lives on `portfolio-redesign`.
- Do not merge the redesign until it has been reviewed and approved.

## Site structure

- `index.html` — portfolio landing page, credentials, honors, and contact
- `resume.html` — public, print-friendly résumé without private phone or home address
- `styles.css` — shared design system and responsive styles
- `documents/` — public verification copies of supporting documents
- `assets/` — social preview and other media
- `favicon.svg` — site icon

## Updating content

Edit the relevant semantic HTML card in `index.html`. Reuse the existing button,
skill-pill, and card classes to keep spacing and styling consistent. Supporting
documents should use descriptive lowercase filenames and must be checked for private
identifiers or third-party contact details before publishing.

No package installation or build command is required. Open `index.html` through a
local static server to review changes.
