# Bansal & Agrawal Chartered Accountants Website

This is a static website for Bansal & Agrawal Chartered Accountants, built with plain HTML and Tailwind CSS (via CDN). All pages are fully static and require no backend or build tools.

## Folder Structure

```
smabansal-main/
├── index.html
├── about.html
├── service.html
├── sector.html
├── team.html
├── contact.html
└── public/
    └── images/
        └── index/
            ├── ... (all image files)
```

## Usage

1. **Open any HTML file** (e.g., `index.html`) directly in your browser.
2. All styling is handled by Tailwind CSS via CDN, so no build step is required.
3. All images are located in `public/images/index/` and referenced in the HTML as `public/images/index/filename.ext`.

## Notes
- No server or Node.js dependencies are required.
- You can deploy this site to any static hosting provider (GitHub Pages, Netlify, Vercel, etc.).
- If you add new images, place them in `public/images/index/` and reference them with the correct path in your HTML. 