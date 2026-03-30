# Tripscape — Landing Page Design Explorations

## What This Is
A design exercise for the MPCS Design-Build-Ship course. We are building **25 distinct landing page iterations** for **Tripscape**, a travel platform, exploring different layouts, moods, visual styles, audiences, and tones.

## What Tripscape Is
Tripscape is a platform that lets users:
- **Create and store travel itineraries** (day-by-day trip plans with stops, notes, maps)
- **Write and share travel guides** (blog-style local knowledge and travel tips)
- **Search and discover** community itineraries and guides
- **Track their world** via a dashboard with an interactive map showing countries visited and % of the world explored

## Project Structure
```
Assignment-1/
├── CLAUDE.md           # This file
├── index.html          # Process narrative page — tells the story of all 25 iterations
├── styles.css          # Styles for index.html
└── iterations/
    ├── 01.html         # Each iteration is a self-contained HTML file
    ├── 02.html         # with inline styles (no shared CSS)
    └── ...
```

## Design Decisions
- **Landing pages are logged-in experiences** (not marketing pages for new users). They show the user's dashboard with their itineraries, guides, map, and explore options.
- Each iteration is a **single self-contained HTML file** with all CSS inlined — no shared stylesheets across iterations.
- Each iteration includes a **back link** to `../index.html`.
- The **index.html** is a process narrative (not a grid gallery) organized into chapters that tell the story of the design evolution, culminating in a final choice section.

## Sample User Data
Use Helena's real travel background for sample content:
- **41 countries**, 6 continents, 23 US National Parks
- Trips: Japan, Patagonia, Iceland, Berlin, Peru, etc.
- Runs: NYC Marathon '24, Berlin Marathon '25
- Hikes: Fuji, Kilimanjaro, Patagonia, national parks

## Tech Constraints
- **HTML and CSS only** — no JavaScript whatsoever
- CSS transitions/animations via `:hover` and `@keyframes` are fine, but no JS-triggered interactions

## Style Preferences
- Each iteration should have a **Tripscape logo** (SVG or text-based, varies by iteration)
- Use **color** — avoid plain black and white designs
- Iterations should vary across: layout, color palette, typography, mood, target audience, and tone
- Include an **interactive SVG world map** on dashboard iterations showing visited countries
- Prefer **system fonts** or web-safe fonts (no external font CDN dependencies)
- All iterations must be **responsive**

## Git Workflow
- Commit each new iteration individually so the design evolution is tracked in git history
- Push to: https://github.com/helenazhang425/dbs-assignment-1
