# Attila Kondor - CV

Source for my online CV at [attilakondor.com](https://attilakondor.com).

Static site, no framework. Vanilla JS + a single CSS file. Light + dark mode, lens-based content tailoring per audience cluster (Security & Policy / Music Tech / Audio Engineering), keyboard-accessible photo gallery, print stylesheet for PDF export.

## Structure

```
.
├── index.html                 main CV
├── gallery.html               photo gallery subpage
├── robots.txt
├── sitemap.xml
└── assets/
    ├── css/main.css           shared stylesheet
    ├── photos/                images
    ├── docs/                  documents linked from the CV
    └── social/og-image.png    Open Graph card image
```

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Lens system

Append `?lens=` to the URL to land on a curated view:

- `?lens=security` - Security & Policy
- `?lens=music-tech` - Music Technology
- `?lens=audio` - Audio Engineering

Without the parameter, the page renders the "all" view.

## Print to PDF

`Cmd+P` triggers an aggressive print stylesheet (chrome and photos hidden, white background, two-column projects, break-inside-avoid on cards). Save as PDF.

## Contact

attilakondor006@gmail.com · [LinkedIn](https://www.linkedin.com/in/attila-kondor-) · [GitHub](https://github.com/dhm-ak)
