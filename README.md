# Personal Website Template

A clean, responsive starter template for a personal website/portfolio.

## Included

- **Hero section** with call-to-action buttons
- **About section**
- **Projects grid**
- **Experience timeline**
- **Contact section**
- **Light/Dark theme toggle** (with localStorage persistence)
- **Mobile-friendly navigation**

## Project Structure

```text
.
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Quick Start

Because this is a static site, you can open it directly:

1. Open `index.html` in your browser

Or serve it locally (optional):

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize

### 1) Personal info
Edit these in `index.html`:

- Page title (`<title>`)
- Name in the logo and hero heading
- About text
- Contact email
- Social/profile links

### 2) Projects and experience
Replace placeholder cards/items in:

- `#projects`
- `#experience`

### 3) Colors and typography
Edit CSS variables in `styles.css`:

- `:root` for light mode
- `body.dark` for dark mode

## Deploy

You can deploy this template to:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
