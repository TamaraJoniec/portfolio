# Tamara Joniec Portfolio

This repository contains a simple static portfolio website for Tamara Joniec. The project is built using plain HTML and CSS (inline styles) and includes the following pages:

- `index.html` — landing page / home view with custom cursor effects and navigation.
- `work.html` — showcases work or projects.
- `cv.html` — provides a résumé / about page.

## Features

- Responsive design with fluid typography and CSS variables for colours, fonts, and layout tokens.
- Custom cursor implementation (`#cursor-dot` and `#cursor-ring`) with hover state transitions.
- Noise overlay background effect for subtle texture.
- Sticky navigation bar with scroll state styling and link highlighting.
- Minimal external dependencies; fonts are loaded from Google Fonts.

## Assets

- `images/` — directory intended for portfolio images used across the site.

## Usage

1. Clone or download the repository.
2. Open any of the HTML files in a web browser to view the site.
3. Modify content directly within the HTML files as needed. Styles are included inline for ease of editing.

## Development

No build tools or package managers are required. The site is purely static:

```bash
# serve locally using Python's simple HTTP server (optional)
cd Tamara-portfolio
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## License

## MIT Licence
