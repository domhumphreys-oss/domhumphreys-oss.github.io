# Dom Humphreys — Personal Website

## Project Overview
Single page personal website for Dom Humphreys, a Product Manager specialising in payments and platforms. Hosted on GitHub Pages at https://domhumphreys-oss.github.io

## File Structure
- `index.html` — the entire site, contains all HTML, CSS and content in one file
- No build system, no frameworks, no dependencies
- Changes are deployed by running: git add . && git commit -m "description" && git push

## Design System
- Fonts: DM Sans (body) and DM Serif Display (headings/logo)
- Background: #fafaf8 (warm off-white)
- Text primary: #111110
- Text secondary: #5f5e5a
- Text tertiary: #888780
- Borders: rgba(0,0,0,0.1)
- Cards/surfaces: #f1efea

## Site Structure (in order)
1. Nav — sticky, logo left, links right
2. Hero — name, tagline, tags, two CTA buttons
3. Highlights — work experience with metric cards
4. Expertise — 6 card grid
5. Blog — coming soon placeholder
6. Contact — email and GitHub link
7. Footer

## Job/Highlight Cards
Each role uses a two-column grid (190px left, 1fr right):
- Left: company name + date range
- Right: title, description, metric cards
- Metric cards use background #f1efea, show a value and a label

## Content Rules
- Phone number is NOT on the site (removed for privacy)
- Email: dominicjohnhumphreys@gmail.com
- GitHub: https://github.com/domhumphreys-oss
- Planet Payments and Simply Business are NOT in highlights (removed by Dom)
- Surf Labs role is "Product Advisor" not "Head of Product"

## Deployment
After any change always remind Dom to run:
git add .
git commit -m "describe the change"
git push
