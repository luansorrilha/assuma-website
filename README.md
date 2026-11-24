# ASSUMA — Institutional Website

**Responsive landing page | Front-end development | UX/UI**

**English** | [Português (BR)](./README.pt-BR.md)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## Overview

An institutional website prototype for ASSUMA (Associação para Sustentabilidade e Meio Ambiente), an environmental association connected to Joaquim Egídio, Campinas, Brazil. Developed as part of the 2026/2 Integrated Multidisciplinary Project (PIM) in Systems Analysis and Development at UNIP.

The project explores how responsive design, accessible interfaces and clear information architecture can communicate environmental initiatives and encourage community engagement.

## Features

- Responsive layout for desktop, tablet and mobile devices.
- Semantic HTML, keyboard-friendly navigation and reduced-motion support.
- Interactive mobile menu, active-section highlighting and scroll-based animations using IntersectionObserver.
- Institutional content, environmental initiatives, photo gallery and participation options.
- Client-side contact form validation and a pre-filled WhatsApp message. No automatic submission, backend or database.

## Technologies

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure and content |
| CSS3 | Visual identity, responsive layout and components |
| Vanilla JavaScript | Navigation, interaction and form validation |

## Run locally

Clone the repository (requires access while private):

```bash
git clone https://github.com/luansorrilha/assuma-website.git
cd assuma-website
```

Open `index.html` in a modern browser or start a local server with Python:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`. An internet connection is required for external photographs, web fonts and the embedded map.

## Project structure

```text
assuma-website/
├── assets/       # Local brand assets
├── docs/         # Academic and design documentation
├── index.html    # Page structure
├── style.css     # Styling and responsiveness
├── script.js     # Client-side interactions
└── README.md
```

## Documentation

- [Academic context, sources and image credits (PT-BR)](./docs/PROJECT_CONTEXT.md)
- [Requirements and test scenarios (PT-BR)](./docs/CHECKLIST_PIM.md)
- [Visual design decisions (PT-BR)](./docs/DECISOES_VISUAIS.md)

## Project status and disclaimer

Academic prototype, not the official ASSUMA website. Institutional copy, contact details and brand usage require confirmation by the association before public release. Illustrative photographs do not necessarily depict ASSUMA activities. Third-party materials remain subject to their respective rights and licenses.

Public demo and screenshots are not yet available.
