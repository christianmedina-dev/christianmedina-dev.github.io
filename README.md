# christianmedina-dev.github.io

Personal engineering portfolio of **Christian J. Medina Díaz**, a Software Engineer focused on **Data Engineering, Backend Systems, and Cloud Architecture**.

Built to serve as a concise, bilingual introduction to my work, engineering experience, technical projects, and approach to building scalable data systems.

**Live portfolio:**
https://christianmedina-dev.github.io

---

## Overview

This repository contains the source for my personal software engineering portfolio.

The site was designed around a simple goal: present technical experience without turning a portfolio into a résumé rendered as a webpage.

It highlights:

* Software engineering and data engineering experience
* Cloud-based data pipelines and analytics workloads
* Backend and relational database work
* Selected academic and personal engineering projects
* Technical writing
* Direct access to my résumé and professional profiles

The experience is fully bilingual in **English and Spanish**.

Visitors first select their preferred language before entering the portfolio, while language switching remains available throughout the site.

---

## Design Philosophy

The portfolio follows a minimal editorial design built around clarity, typography, and content.

Rather than relying on a large frontend framework, the site intentionally uses a lightweight static architecture.

The visual system combines:

* Warm cream background
* Near-black typography
* Red accent color
* **Instrument Serif** for editorial headings
* **IBM Plex Mono** for technical and interface elements

The responsive experience was designed independently for desktop and mobile rather than simply shrinking the desktop layout.

Mobile layouts account for:

* iOS and Android browsers
* Safe-area insets
* Responsive typography
* Touch-friendly navigation
* Dedicated mobile menu behavior
* Controlled content widths
* Mobile-first spacing and composition

---

## Features

### Bilingual Experience

The site supports:

* 🇺🇸 English
* 🇵🇷 Español

A dedicated language entry screen introduces the portfolio before the main content is displayed.

Visitors can also switch languages later through the navigation menu.

### Responsive Design

The interface adapts across:

* Desktop
* Tablet
* iPhone / iOS browsers
* Android browsers

The mobile experience uses its own layout rules for navigation, typography, content hierarchy, project sections, metrics, and calls to action.

### Professional Portfolio

The main portfolio includes:

* About
* Professional experience
* Selected engineering projects
* Technical skills
* Education
* Contact information
* Downloadable résumé

### Technical Writing

The repository also contains a standalone engineering essay:

**Cloud cost is not an invoice, it is a design decision**

The essay discusses data ingestion architecture and the engineering decisions behind moving workloads from full refresh patterns toward incremental processing.

### Social Preview

Open Graph and social metadata provide a custom preview when the portfolio is shared through supported platforms.

The preview mirrors the site's language-entry experience to maintain visual continuity between the shared link and the portfolio itself.

---

## Technology

The site intentionally keeps its technical footprint small.

**Frontend**

* HTML5
* CSS3
* Vanilla JavaScript

**Browser APIs**

* `localStorage`
* Responsive viewport and safe-area APIs
* Native DOM APIs

**Typography**

* Instrument Serif
* IBM Plex Mono

**Hosting**

* GitHub Pages

There is no application framework, package manager, compilation process, or production build pipeline required to run the portfolio.

---

## Project Structure

```text
christianmedina-dev.github.io/
│
├── index.html
├── ensayo.html
├── portrait.webp
├── preview-cream.png
│
├── cv/
│   └── Christian-Medina-CV.pdf
│
└── README.md
```

### `index.html`

Main bilingual portfolio and language-entry experience.

Contains the responsive layout, navigation, language management, portfolio sections, and social metadata.

### `ensayo.html`

Standalone technical essay focused on cloud and data ingestion architecture.

### `portrait.webp`

Optimized portrait used within the portfolio.

### `preview-cream.png`

1200 × 630 social preview image used by Open Graph-compatible platforms when the website is shared.

### `cv/`

Contains the downloadable résumé linked from the portfolio.

---

## Running Locally

No dependencies need to be installed.

Clone the repository:

```bash
git clone https://github.com/christianmedina-dev/christianmedina-dev.github.io.git
cd christianmedina-dev.github.io
```

Start any local static HTTP server.

Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Changes to the static files can be tested immediately by refreshing the browser.

---

## Deployment

The portfolio is hosted directly through **GitHub Pages**.

Changes deployed to the configured publishing branch are served at:

```text
https://christianmedina-dev.github.io
```

Because the site is completely static, deployment does not require a separate build process.

---

## Engineering Focus

My current engineering interests center around:

```text
Data Engineering
     ↓
Backend Systems
     ↓
Cloud Architecture
     ↓
Scalable Data Platforms
```

My professional work includes designing and optimizing data workflows involving millions of records, relational databases, cloud infrastructure, analytics platforms, and business intelligence systems.

Technologies I regularly work with include:

`Python` · `SQL` · `AWS` · `PostgreSQL` · `MySQL` · `Power BI` · `QuickSight` · `Flask` · `REST APIs`

---

## Contact

**Christian J. Medina Díaz**
Software Engineer · Data & Cloud
San Juan, Puerto Rico

Email: [cjmedina99@gmail.com](mailto:cjmedina99@gmail.com)
LinkedIn: https://linkedin.com/in/christian-medina-1a1796198/
GitHub: https://github.com/christianmedina-dev

---

<p align="center">
  <strong>Systems should not just hold data. They should make it useful.</strong>
</p>
