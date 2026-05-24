# Barjo Science Fair Website

## Project Overview

Static HTML website for the Barjo Science Fair — a community science fair for students at Barrington Elementary and Jones Middle School (Upper Arlington, OH).

- **Domain:** barjosciencefair.com
- **Hosting:** GitHub Pages (CNAME file present)
- **Contact:** barjo@barjosciencefair.com
- **Analytics:** Google Analytics (G-F3WPYBQMND)

## Structure

Single-page site — everything is in `index.html`. No build system, no framework, no dependencies.

- `index.html` — the entire site
- `logo.png` — header logo
- `CNAME` — GitHub Pages custom domain config
- `materials/` — supplementary files (e.g., PDF resources)

## Key Content Areas

- Header with logo and action button(s)
- Yellow banner for announcements
- Main content sections: Why Participate, Guidelines, How to Get Started, District/Regional Participation, Timeline, Judging/Volunteering
- Footer with contact email

## Conventions

- Colors defined as CSS custom properties in `:root` (primary orange `#df9109`, secondary `#f5b663`)
- Max content width: 900px
- Buttons: `.btn` class on `<a>` tags
- Timeline events: `.timeline > .event` with `.date` paragraph
- Resource lists: `<dl>/<dt>/<dd>` pattern with linked `<dt>` and description `<dd>`
- No JavaScript except Google Analytics

## Deployment

Push to `main` branch; GitHub Pages serves automatically.

## Yearly Updates

Each fair cycle, update:
1. Fair date and times throughout the page
2. Timeline section key dates
3. Banner announcement
4. Button links (registration forms, etc.)
5. Footer copyright year
