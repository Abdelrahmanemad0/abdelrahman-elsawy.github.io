# Abdelrahman Elsawy — Personal Portfolio

Source for [abdelrahman-elsawy.github.io](https://abdelrahman-elsawy.github.io), my personal portfolio site: a single-page site covering education, work experience, and featured AI/ML, embedded systems, and robotics projects.

## Tech Stack

- Plain HTML5 + CSS3 (custom properties, canvas-based particle background, scroll-reveal animations)
- Vanilla JavaScript — no framework, no build step, no dependencies
- Hosted on GitHub Pages

## Project Structure

```
.
├── index.html    # Entire site: markup, styles, and scripts in one file
└── README.md
```

## Running Locally

No build step required. Either open `index.html` directly in a browser, or serve it with any static file server, e.g.:

```bash
python3 -m http.server
```

## Editing

All content (hero, about, experience, projects, contact) lives in `index.html`, top to bottom in the order it appears on the page. Styling is in the `<style>` block at the top of the file.

## Deployment

This site is served by GitHub Pages directly from the `main` branch. Any push to `main` updates the live site at https://abdelrahman-elsawy.github.io within a minute or two.

## License

See [LICENSE](LICENSE).
