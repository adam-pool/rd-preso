# Race & Development Event Planning Presentation

A simple, self-contained presentation built with [Reveal.js](https://revealjs.com/).

## Viewing the Presentation

### Local Viewing
Simply open `index.html` in any modern web browser:
```bash
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

Or use a simple HTTP server:
```bash
python3 -m http.server 8000
# Then open http://localhost:8000
```

### Hosting
This is a static HTML presentation that can be hosted anywhere:
- **GitHub Pages**: Enable in repository settings → Pages → Deploy from branch
- **Netlify**: Drag and drop the repository folder
- **Vercel**: Connect repository and deploy
- **Any static host**: Upload `index.html` and access via URL

## Navigation
- **Next slide**: Space, →, ↓, or click
- **Previous slide**: ←, ↑
- **Overview mode**: Press `Esc` or `O`
- **Fullscreen**: Press `F`
- **Speaker notes**: Press `S` (if enabled)

## Customization

### Themes
Change the theme by modifying the CSS link in `index.html`:
- `black.css` (default)
- `white.css`
- `league.css`
- `beige.css`
- `sky.css`
- `night.css`
- `serif.css`
- `simple.css`
- `solarized.css`

### Content
Edit the `<section>` elements in `index.html` to modify slide content. Nested `<section>` elements create vertical slides.

## Source Material
Presentation content is based on `race_event_plan.md`.