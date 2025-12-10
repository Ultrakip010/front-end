# Portfolio Front-End

A simple, static portfolio website built with HTML and CSS. It showcases sections for Home, Ervaring (Experience), Over mij (About me), and Contact. The site content is primarily in Dutch.

## Quick Start

1. Clone or download this repository to your machine.
2. Open `index.html` directly in your browser (double‑click or drag it into a browser window).

No build step or dependencies are required.

## Project Structure

```
front-end/
├── index.html      # Main HTML page
├── main.css        # Stylesheet
└── img/            # Images used on the site
```

## Features

- Responsive navigation with anchors to page sections
- Sections:
  - Home: Title, welcome text, social links
  - Ervaring: Three project previews with images
  - Over mij: Cards describing background, education, and future plans
  - Contact: Simple form (static; no backend wired up)
- Footer with email, phone, and region information

## Editing Content

- Text: Edit the copy directly in `index.html`.
- Styles: Adjust colors, spacing, or layout in `main.css`.
- Images: Replace files in the `img` folder and update `src` paths in `index.html` if filenames change.

## Social Links

The Home section includes icons for LinkedIn, Instagram, and Facebook. Update the `href` values in `index.html` to point to your real profiles.

## Contact Form

The form posts to `/submit_contact_form`, which is a placeholder. To make it functional, you can:

- Connect it to a backend route that accepts POST requests, or
- Use a form service (e.g., Formspree, Netlify Forms) and replace the `action` with the service endpoint.

## Deployment

Because this is a static site, you can host it easily using:

- GitHub Pages: Serve the repository root.
- Netlify/Vercel: Drag‑and‑drop or connect the repo; set the publish directory to the project root.
- Any static host: Upload `index.html`, `main.css`, and the `img` folder.

## Preview

Open `index.html` in your browser. Ensure the `img` folder remains alongside the file so images load correctly.

## License

This project is provided as‑is for personal portfolio use. If you reuse parts of it, please provide attribution.
