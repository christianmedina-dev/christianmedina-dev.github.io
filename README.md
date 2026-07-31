# christianmedina-dev.github.io

Personal site of **Christian J. Medina Díaz** — Software Engineer working in data systems and cloud pipelines.

**Live:** https://christianmedina-dev.github.io

## About this site

A bilingual (ES/EN) one-page portfolio: background, experience, selected projects and contact, plus a technical essay on ingestion design. Built as a static site — no build step, no framework, no dependencies to install.

- `index.html` — main page
- `ensayo.html` — technical essay: *Cloud cost is not an invoice, it is a design decision*
- `cv/` — resumé (PDF)

## Stack

Plain HTML with inline styles, a small runtime for the interactive parts, and `IntersectionObserver` for scroll reveals. Typography: Instrument Serif + IBM Plex Mono. Language preference persists in `localStorage`.

Hosted on GitHub Pages.

## Running locally

Any static server works:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Contact

- Email — cjmedina99@gmail.com
- LinkedIn — [christian-medina](https://linkedin.com/in/christian-medina-1a1796198/)
