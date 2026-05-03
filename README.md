# HowOldIam — Free Age Calculator Tools

A collection of free, fast, and privacy-friendly age calculator tools built with vanilla HTML, CSS, and JavaScript. No frameworks. No dependencies. No data collection.

🌐 **Live site:** [howoldiam.netlify.app](https://howoldiam.netlify.app)

---

## Tools included

### 1. Age Calculator
Find your exact age in years, months, days, hours, and minutes. Also shows the total number of days you have been alive and counts down to your next birthday.

### 2. How Old Was I?
Enter your date of birth and click any year to instantly see how old you were — or will be — in that year. Great for nostalgic moments or future planning.

### 3. Age Difference Calculator
Find the exact age gap between two people. Enter names and dates of birth for both people and instantly see who is older and by exactly how much.

---

## Features

- ⚡ Instant results — all calculations run in the browser
- 📱 Fully responsive — works on mobile, tablet, and desktop
- 🔒 Zero data collection — nothing is stored or transmitted
- ♿ Accessible — semantic HTML, keyboard navigation supported
- 🔍 SEO optimised — meta tags, canonical URLs, FAQ schema, WebApp schema
- 🚀 Fast loading — no frameworks, no external dependencies

---

## Tech stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, CSS Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — DM Sans & DM Serif Display |
| Hosting | Netlify |
| SEO | JSON-LD schema (FAQPage + WebApplication) |

---

## Project structure

```
howoldiam/
├── index.html                      # Age Calculator (homepage)
├── how-old-was-i.html              # How Old Was I? tool
├── age-difference-calculator.html  # Age Difference Calculator
├── privacy.html                    # Privacy policy
├── sitemap.xml                     # XML sitemap for Google
├── robots.txt                      # Search engine crawl rules
└── README.md                       # You are here
```

---

## SEO implementation

Each page includes:
- Keyword-first `<title>` tag
- Meta description under 155 characters
- Canonical URL tag
- Open Graph tags for social sharing
- `FAQPage` JSON-LD schema for rich snippets
- `WebApplication` JSON-LD schema
- Internal links between all tool pages

---

## Running locally

No build step required. Just open any `.html` file directly in your browser:

```bash
git clone https://github.com/yourusername/howoldiam.git
cd howoldiam
open index.html
```

Or use a local server for cleaner URL routing:

```bash
npx serve .
```

---

## Deployment

The site is deployed on Netlify via GitHub integration. Every push to the `main` branch triggers an automatic deployment.

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-BADGE-ID/deploy-status)](https://app.netlify.com/sites/howoldiam/deploys)

---

## License

MIT — free to use, modify, and distribute.

---

## Author

Built and maintained by [@yourusername](https://github.com/yourusername)
