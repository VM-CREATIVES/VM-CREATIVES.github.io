# VM CREATIVES Website

Static website for VM CREATIVES. Open `index.html` directly or serve this folder with a local/static web server.

## Pages

- `index.html`
- `about.html`
- `pages/services.html`
- `pages/case-studies.html`
- `contact.html`

## Project Structure

```
VM-CREATIVES.github.io/
├── index.html
├── about.html
├── contact.html
├── css/
│   ├── style.css
│   ├── animations.css
│   └── responsive.css
├── js/
│   ├── main.js
│   ├── animations.js
│   └── contact.js
├── assets/
│   ├── favicon.svg
│   └── vm-studio-poster.png
├── pages/
│   ├── services.html
│   └── case-studies.html
├── _headers
├── robots.txt
└── .nojekyll
```

All paths are relative, so the site renders correctly both locally (open `index.html` directly) and when deployed to any static host or subpath.

## Deployment Notes

The site has no build step and no external runtime dependencies. The `_headers` file is included for static hosts that support it, such as Netlify-style deployments.

The contract form CTA points to `https://tally.so/r/684ejA`.

Before going live, confirm the final domain, location wording, phone number, email address, social links, real project case studies, and any privacy/legal text required for your market.
