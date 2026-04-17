# Julian Macias PMHNP-BC — Portfolio Site

## Project Overview
Single-page portfolio site for Julian Macias, Board-Certified Psychiatric Nurse Practitioner specializing in IV ketamine infusion therapy and TMS in Los Angeles, CA.

## Stack
- **Single file**: `index.html` — all HTML, CSS, and JavaScript inline
- **No build step** — edit and open directly in a browser
- **Static hosting** — deployable to GitHub Pages, Netlify, Vercel, or any static host

## Key Files
| File | Purpose |
|------|---------|
| `index.html` | Entire site (HTML + CSS + JS, ~1200 lines) |
| `headshot.jpg` | Local headshot backup |
| `JMaciasPMHNP.pdf` | CV/resume download |

## Development Workflow
```bash
# Open locally
open index.html

# Or serve with a local dev server to avoid CORS issues
npx serve .
python3 -m http.server 8080
```

## Site Sections
1. **Nav** — fixed pill nav with smooth-scroll links
2. **Hero** — name, credentials, headshot, CTA buttons
3. **About** — bio with animated stats
4. **Services** — ketamine infusion, TMS therapy, consultation cards
5. **Experience** — timeline of clinical positions
6. **Contact** — contact form + info cards

## Deployment
The site is hosted as a static file. To deploy updates:
1. Edit `index.html`
2. Commit and push to `main`
3. Hosting provider auto-deploys from the main branch

## Mission Control Context
- **Project type**: Static web — no server, no database
- **Primary goal**: Showcase Julian's clinical credentials and drive patient inquiries
- **Key metric**: Contact form submissions and CV downloads
- **Tone**: Professional, clinical, reassuring — avoid casual language
