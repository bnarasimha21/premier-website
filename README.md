# Premier Website

A clean, responsive landing page template for website building services. Built with pure HTML and CSS, and deployed automatically to DigitalOcean App Platform via GitHub Actions.

## Features

- **Responsive design** that adapts to all screen sizes
- **About Us section** with business description
- **Services showcase** listing web design, eCommerce, CMS, SEO, and maintenance offerings
- **Portfolio section** for highlighting completed projects
- **Contact form** with name, email, and message fields
- **Automated deployment** to DigitalOcean App Platform on push to main

## Tech Stack

- **Languages:** HTML5, CSS3
- **Hosting:** DigitalOcean App Platform
- **CI/CD:** GitHub Actions
- **Deployment:** DigitalOcean App Action v2

## Setup / Installation

No build tools or dependencies required:

```bash
git clone https://github.com/bnarasimha21/premier-website.git
cd premier-website
open index.html
```

### Deployment to DigitalOcean

The project is configured for automatic deployment to DigitalOcean App Platform:

1. Set the `DIGITALOCEAN_ACCESS_TOKEN` secret in your GitHub repository settings
2. Push to the `main` branch -- the GitHub Actions workflow will automatically deploy the site

## Usage

- Edit `index.html` to customize the content, services, portfolio items, and contact information
- Modify the inline `<style>` block or link an external CSS file to change the visual design
- The contact form action should be updated to point to your form-handling backend or service

## License

MIT
