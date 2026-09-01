# Pylko Concept

A two-page website concept for the Pylko café, focused on its coffee-and-pyshki atmosphere in Saint Petersburg.

## Demo

No hosted demo is currently available. The project runs locally as a static website.

## About

The concept translates the venue's visual character into a compact web experience with a story-led home page and a dedicated menu page. The supplied local photography is integrated into the layout rather than used as page screenshots.

## Features

- Responsive home and menu pages
- Image-led editorial layout
- Shared navigation and visual system
- Café story, atmosphere, menu, and visit sections
- Local assets with no external runtime dependencies

## Tech Stack

- HTML5
- CSS3
- Static PNG assets

## Architecture

`index.html` is the main concept page, `menu.html` contains the menu experience, and both pages share `style.css`. All imagery is stored locally in `assets/`; there is no JavaScript, backend, package manager, or build step.

## My role

I created the page concept, information hierarchy, responsive HTML/CSS implementation, two-page navigation, and integration of the supplied venue imagery.

## Screenshots

Screenshots can be added after the concept is deployed. Representative project imagery is available in `assets/`.

## Running locally

```bash
python3 -m http.server 8080
```

Open http://localhost:8080. You can also open `index.html` directly in a browser.

## Status

Portfolio concept project.

