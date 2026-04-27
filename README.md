# Archit Sharma Portfolio

A responsive personal portfolio for Archit Sharma, focused on DevOps learning, cloud deployment, and practical web projects.

The site is built with plain HTML and CSS, so it can be hosted easily on GitHub Pages, AWS EC2 with Nginx, or any static hosting service.

## Live Sections

- Hero introduction with profile image
- About section
- Project highlights
- Skills and tools
- Deployment workflow summary
- Contact links

## Tech Stack

- HTML5
- CSS3
- Responsive layout with media queries
- Static image assets

## Project Structure

```text
.
├── index.html
├── styles.css
├── profile-portrait.jpg
├── profile.jpg
├── resume.txt
├── summary.txt
└── README.md
```

## Run Locally

Because this is a static website, no build step is required.

Open `index.html` directly in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This portfolio is intended to be deployed as a static site. A common setup is:

1. Push the project to GitHub.
2. Deploy the files to an AWS EC2 instance.
3. Serve the site with Nginx.
4. Point a custom domain through Cloudflare.
5. Enable HTTPS using Let's Encrypt SSL.

It can also be deployed through GitHub Pages by publishing the repository from the main branch.

## Featured Skills

- AWS EC2
- Nginx
- Linux
- Git and GitHub
- Cloudflare DNS/CDN
- SSL setup
- Node.js basics
- Docker learning
- CI/CD fundamentals

## Contact

- Email: [it.architsharma.69@gmail.com](mailto:it.architsharma.69@gmail.com)
- GitHub: [Archit1704](https://github.com/Archit1704)
- LinkedIn: [Archit Sharma](https://www.linkedin.com/in/archit-sharma-0310ms)
