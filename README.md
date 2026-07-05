# Open Autonomyx Research Development

Static GitHub Pages site for **research.openautonomyx.com**.

## Pages URL

- Custom domain: <https://research.openautonomyx.com>
- Repository: <https://github.com/Open-Autonomyx/Research-Development>

## Contents

- `index.html` — landing page
- `agentic-research.html` — article page
- `assets/cover.svg` — blog cover image
- `styles.css` — site styling
- `CNAME` — GitHub Pages custom domain
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow

## DNS required

Create a DNS record for the subdomain:

```txt
Type: CNAME
Name: research
Value: open-autonomyx.github.io
```

After DNS propagates, enable HTTPS in GitHub Pages settings if it is not already enforced automatically.
