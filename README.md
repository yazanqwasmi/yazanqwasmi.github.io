# Yazan Qwasmi — Portfolio Site

[\![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white)](https://www.w3.org/html)
[\![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://www.w3.org/TR/CSS)
[\![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[\![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-181717?logo=github)](https://pages.github.com)

## Overview

Professional portfolio website showcasing full-stack and machine learning projects. Clean, responsive design hosted on GitHub Pages with seamless navigation, project showcases, and contact integration.

## Key Features

- **Responsive Design**: Mobile-first, works on all device sizes
- **Project Portfolio**: Curated showcase of full-stack, ML, and hardware projects
- **About Section**: Professional bio and skillset summary
- **Contact Integration**: Email and social media links
- **Fast Load Times**: Static site optimization
- **SEO-Optimized**: Meta tags and semantic HTML

## Tech Stack

**Frontend:** HTML5, CSS3, Vanilla JavaScript  
**Hosting:** GitHub Pages  
**Performance:** Static site generation, no build step required  

## Getting Started

### View Live
Visit: `https://yazanqwasmi.github.io`

### Local Development

```bash
git clone <repo-url>
cd yazanqwasmi.github.io

# Serve locally (requires Python 3)
python -m http.server 8000

# Navigate to http://localhost:8000
```

## Project Structure

```
├── index.html              # Home page
├── css/
│   └── styles.css         # Global styles
├── js/
│   └── main.js            # Interactive elements
├── projects/
│   ├── bms.html
│   ├── stock-predictor.html
│   └── ...                # Individual project pages
├── assets/
│   ├── images/
│   └── cv/
└── README.md
```

## Customization

**Update About Section:**  
Edit `index.html` → `<section id="about">`

**Add Project:**  
1. Create `projects/my-project.html`
2. Link from `index.html` project gallery
3. Add project card with thumbnail and description

**Modify Styles:**  
Edit `css/styles.css` — uses CSS custom properties for easy theme changes

```css
:root {
  --primary-color: #0066cc;
  --text-color: #333;
  --bg-color: #fff;
}
```

## Deployment

Site auto-deploys on push to `main` branch via GitHub Pages. No additional setup needed.

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

Live in ~1 minute at `https://yazanqwasmi.github.io`

## Performance Optimization

- **No frameworks needed** — vanilla JS keeps bundle minimal
- **Image optimization** — WebP fallbacks for modern browsers
- **CSS minification** — Single stylesheet load
- **Cache headers** — GitHub Pages handles with smart defaults

## License

[Add your license]
