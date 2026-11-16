# Ken Weill Lumacad | Online Resume

Personal resume website of Ken Weill Lumacad, Affiliate Marketing Manager and WordPress & SEO Specialist.

**Live site: [kenweill.com](https://kenweill.com)**

## About

A single-page, responsive resume built with plain HTML and CSS. No frameworks, no build step, and no dependencies other than Google Fonts.

## Features

- Two-column layout with sidebar (contact, core skills, education, certifications) and main content (summary, experience, open source projects)
- Fully responsive for desktop, tablet, and mobile
- Print-friendly styling with a floating print button to save as PDF
- Profile picture with automatic fallback to initials if the image fails to load
- Fast loading, single HTML file with inline CSS

## Repository Structure

| File | Description |
| --- | --- |
| `index.html` | The full resume page (HTML and CSS) |
| `profile-picture.png` | Profile photo shown in the sidebar |
| `CNAME` | Custom domain configuration for kenweill.com |
| `404.html` | Custom "page not found" page |
| `robots.txt` | Search engine crawling rules |
| `sitemap.xml` | Sitemap for search engines |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (skips Jekyll processing) |
| `.gitignore` | Files and folders Git should ignore |
| `LICENSE` | MIT License (code only, see below) |

## Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/kenweill/my-resume.git
   ```
2. Open `index.html` in any browser.

## Deployment

The site is served from this repository on the custom domain [kenweill.com](https://kenweill.com), configured through the `CNAME` file.

## Customizing

To reuse this layout for your own resume, edit the content in `index.html` and replace `profile-picture.png` with your own photo. Colors are controlled by the CSS variables at the top of the stylesheet (`:root`).

## Related Projects

- [MikhMon CE](https://github.com/kenweill/mikhmon-ce)
- [KWL Maintenance Mode](https://github.com/kenweill/kwl-maintenance-mode)
- [KWL Coupon WP](https://github.com/kenweill/kwl-coupon-wp)
- [KWL Resume](https://github.com/kenweill/kwl-resume) (WordPress theme version)

## License

The HTML and CSS code in this repository is released under the [MIT License](LICENSE). You are free to use it as a template for your own resume.

The personal content (name, work history, contact details, certifications, and `profile-picture.png`) is not covered by the MIT License and remains all rights reserved. Please replace it with your own if you reuse the layout.

## Contact

- Website: [kenweill.com](https://kenweill.com)
- LinkedIn: [linkedin.com/in/kenweill](https://linkedin.com/in/kenweill)
- GitHub: [github.com/kenweill](https://github.com/kenweill)
