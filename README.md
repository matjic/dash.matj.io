# Dash Website

This directory contains the static marketing website for Dash.

## Structure

```
website/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── styles.css          # Shared stylesheet
├── screenshots/        # App screenshots
└── README.md          # This file
```

## Features

- Responsive design that works on all devices
- Modern gradient design with orange accent colors
- Smooth scrolling navigation
- Feature showcase with 9 key features
- Screenshot gallery
- Privacy policy page
- App Store download link placeholders

## Development

This is a static website with no build process required. Simply open `index.html` in a browser to view locally.

To serve locally with live reload:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js http-server
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Deployment

This website can be deployed to any static hosting service:

- **GitHub Pages**: Push to a `gh-pages` branch
- **Netlify**: Connect your repository and deploy
- **Vercel**: Import from GitHub
- **Cloudflare Pages**: Connect repository

## Customization

### Colors

The website uses an orange color scheme:
- Primary: `#f97316` (orange-500)
- Hover: `#ea580c` (orange-600)

To change colors, update the CSS variables in `styles.css`:
- `.nav-brand h1` - Brand color
- `.btn-primary` - Button colors
- `.feature-card` - Card backgrounds
- Hero and download section gradients

### Content

Update content directly in `index.html`:
- Hero section (lines 30-60)
- Features (lines 65-110)
- Screenshots (lines 115-130)
- Download section (lines 135-150)

### App Store Links

Replace placeholder links with actual App Store URLs:
- Line 40 in `index.html`
- Line 137 in `index.html`

## Screenshots

To add more screenshots:

1. Place PNG files in the `screenshots/` directory
2. Update the screenshots grid in `index.html` (around line 120)
3. Follow the existing markup pattern

## License

This website template is based on the Close app website and adapted for Dash.
