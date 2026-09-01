# Codeup Design

A responsive static marketing site for a creative design studio. The project presents a visual brand identity, service offerings, portfolio highlights, and a call-to-action for prospective clients.

**[View the live site](https://chininchu.github.io/Codeup-Design-Project/)**

## Overview

This project focuses on front-end structure and visual design. It includes:

- a responsive navigation bar
- a hero section with branded CTAs
- portfolio/project cards
- service and about sections
- a contact callout and footer

## Project Structure

- `index.html` — main page structure and content
- `design-project.css` — custom styling and layout rules
- `assets/images/` — branding and project imagery
- `_headers` — Netlify security headers for the site

## Run the Project

You can view the page by opening `index.html` directly in the browser, or by serving it locally.

### Local preview

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Security

This project includes several browser hardening measures to reduce common front-end risks:

- Content Security Policy (CSP)
- `X-Frame-Options: DENY`
- `X-Content-Type-Options: nosniff`
- HTTP Strict Transport Security (HSTS)
- Referrer and permissions restrictions

These headers help reduce XSS risk, clickjacking, MIME confusion, and unnecessary browser exposure.

## Notes

This is a static front-end project, so the focus is on clean structure, readable markup, and practical security hardening rather than complex application logic.
