# Sriram G S — Developer Portfolio

Live site: **[gssriram.live](https://gssriram.live/)**

Personal portfolio and single-page resume site for **Sriram G S**, B.Tech Information Technology student at Karpagam College of Engineering (KCE), Coimbatore, and competitive programmer with 2000+ problems solved across LeetCode, CodeChef, Codeforces, GeeksforGeeks, HackerRank, HackerEarth, and Coding Ninjas.

## Tech Stack

- **HTML5** — semantic single-page structure
- **CSS3** — via Tailwind CSS v3.4.17 (purged utility build)
- **Vanilla JavaScript** — page navigation, dynamic content rendering, theming
- No build step / framework — static site, deployed directly via GitHub Pages

## Features

- 🎨 Configurable theming (colors, fonts) via CSS custom properties — set once, no visitor-facing toggle
- 📱 Fully mobile responsive layout
- 🔍 SEO optimized — meta tags, Open Graph & Twitter Card previews, canonical URL, JSON-LD structured data (`Person` + `SiteNavigationElement`)
- 🗺️ `sitemap.xml` and `robots.txt` configured for search engine and AI crawler discovery
- 🔗 Consolidated links to coding profiles (LeetCode, CodeChef, Codeforces, GeeksforGeeks, HackerRank, Code360), academic profiles (ORCID, Google Scholar, ResearchGate), and social/professional profiles (GitHub, LinkedIn, X, Instagram, Facebook, Medium, Notion, Canva)
- 📄 Downloadable resume (`/resume.pdf`)
- 🖱️ Interactive sections: Home, Education, Skills, Projects, Technical Profiles, Work Experience, Certifications, Achievements, Contact

## Project Structure

```
.
├── index.html                     # Single-page site (markup, styles, and logic)
├── 404.html                       # Custom not-found page (noindex)
├── resume.pdf                     # Resume (title/author metadata set)
├── profile.jpg                    # Profile photo
├── og-image.jpg                   # 1200x630 social preview card
├── favicon.ico                    # Multi-size (16/32/48/64) icon at site root
├── favicon.png                    # 64x64 logo
├── favicon-16x16.png / -32x32.png / -48x48.png
├── apple-touch-icon.png           # 180x180 iOS icon
├── sitemap.xml                    # Sitemap incl. image entries
├── robots.txt                     # Crawler rules (search + AI crawlers)
├── llms.txt                       # Machine-readable site summary for AI assistants
├── zoho-domain-verification.html  # Zoho Mail domain verification (do not edit)
├── CNAME                          # Custom domain config for GitHub Pages
└── README.md
```

## Deployment

This site is deployed via **GitHub Pages** on the custom domain `gssriram.live` (configured via the `CNAME` file). Pushing to the default branch redeploys the live site automatically.

## Contact

- 📧 [gssriram9050@gmail.com](mailto:gssriram9050@gmail.com)
- 💼 [linkedin.com/in/gssriramofficial](https://www.linkedin.com/in/gssriramofficial)
- 🐙 [github.com/gssriram9050](https://github.com/gssriram9050)
