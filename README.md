# Md Mamunur Rahaman – Academic Personal Website

A static academic portfolio website deployed on GitHub Pages.

**Live site:** [https://imamunur.github.io](https://imamunur.github.io)

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage with bio and research summary |
| `publications.html` | Journal articles, conference papers, presentations |
| `service.html` | Editorial board, reviewing, invited talks, society memberships |
| `cv.html` | CV page with link to downloadable PDF |
| `teaching.html` | Teaching experience at UNSW and BRAC University |

## Run Locally

This is a plain static site (HTML + CSS). No build tools or frameworks required.

**Option 1 – Open directly:**
```bash
open index.html
# or on Linux: xdg-open index.html
```

**Option 2 – Local HTTP server (recommended for proper path resolution):**
```bash
# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

**Option 3 – Using Node.js:**
```bash
npx serve .
```

## Project Structure

```
.
├── index.html              # About / homepage
├── publications.html       # Publications
├── service.html            # Professional service
├── cv.html                 # Curriculum Vitae
├── teaching.html           # Teaching experience
├── assets/
│   ├── css/style.css       # Stylesheet
│   ├── img/profile.jpg     # Profile photo
│   └── pdf/                # CV PDF (upload mamunur_rahaman_cv.pdf)
├── .nojekyll               # Tells GitHub Pages to skip Jekyll processing
├── .gitignore
└── README.md
```

## Updating Content

Edit the HTML files directly. All pages share the same CSS (`assets/css/style.css`) and navigation structure.

To update the profile photo, replace `assets/img/profile.jpg`.

To add the CV PDF, place it at `assets/pdf/mamunur_rahaman_cv.pdf`.
