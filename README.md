# flowconnor.dev

Personal portfolio website built with vanilla HTML, CSS, and JavaScript. Originally designed in Webflow, now deployed on Vercel.

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Hosting**: Vercel
- **Domain**: [flowconnor.dev](https://flowconnor.dev)
- **Forms**: Formspree
- **Fonts**: Google Fonts (Manrope)

## Project Structure

```
site/
├── index.html          # Main page
├── css/                # Stylesheets
├── js/                 # JavaScript
├── images/             # Assets
└── vercel.json         # Deployment config
```

## Development

```bash
# Local server
python -m http.server 8000
# or
npx serve .
```

## Deployment

Deploys automatically to Vercel on push to `main`. Configured via `vercel.json`.

**Manual deploy:**
```bash
vercel --prod
```

## Links

- **Live Site**: [flowconnor.dev](https://flowconnor.dev)
- **Form Dashboard**: [Formspree](https://formspree.io/forms/mnqklnog/submissions)
