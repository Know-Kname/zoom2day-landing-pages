# Zoom2Day Landing Pages

## Purpose
Static landing pages for Zoom2Day courier services and The Flower Loft florist. Four conversion-optimized pages targeting different audience segments.

## Tech Stack
- Static HTML/CSS (no framework)
- Shared CSS design system in `/css/style.css`
- Deployed to Vercel as static site

## Pages
| Path | Business | Audience | CTA |
|------|----------|----------|-----|
| `/medical/` | Zoom2Day | Medical B2B | Get SLA Quote |
| `/legal/` | Zoom2Day | Legal B2B | Free First Filing |
| `/sympathy/` | The Flower Loft | Sympathy B2C | View Arrangements |
| `/corporate/` | The Flower Loft | Corporate B2B | Request Bulk Pricing |

## Key Commands
- No build step needed (static HTML)
- `vercel` to deploy
- `vercel --prod` for production deployment

## Structure
```
index.html          # Hub page linking all 4 LPs
css/style.css       # Shared design system
medical/index.html  # Medical B2B landing page
legal/index.html    # Legal B2B landing page
sympathy/index.html # Sympathy B2C landing page
corporate/index.html # Corporate Gifting B2B landing page
```

## GitHub
- Repo: Know-Kname/zoom2day-landing-pages
- Branch: main
