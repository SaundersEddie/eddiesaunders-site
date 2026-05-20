# eddiesaunders.com

Personal portfolio and project site for Eddie Saunders.

This site is being rebuilt as a cleaner, faster, more maintainable home for my coding projects, creative work, drone/aerial notes, music, garden experiments, and assorted nonsense with intent.

The goal is simple: replace the old GoDaddy-hosted site with a modern static site hosted on Cloudflare Pages, while making it easier to show real projects, real writeups, and real working code.

## Live Site

Production domain:

```text
https://eddiesaunders.com
```

Current development / preview deployment:

```text
https://eddiesaunders-site.hippygoth.workers.dev/
```

## Tech Stack

- Astro
- TypeScript
- CSS
- Cloudflare Pages
- GitHub-based deployment workflow

## Project Goals

This site is designed to be:

- Fast and lightweight
- Easy to maintain
- Portfolio-friendly
- Good for technical writeups
- Flexible enough for code, crafts, drone notes, music, and future projects

No bloated site builder. No mystery GoDaddy nonsense. Just files, components, CSS, and deploys that make sense.

## Main Sections

### Home

Landing page and quick introduction.

### Code

Portfolio area for software projects, automation tools, test projects, and technical experiments.

Current and planned highlights include:

- WMATA rail summary tools
- Weather SPA
- Playwright testing portfolio projects
- Python Sudoku logic project
- Social media post generator
- Portfolio Playwright demo

### Creations

Woodworking, CNC, laser, 3D printing, and handmade product work.

### Aerial Notes

Drone and aerial content area, including Part 107 progress notes and future certified drone work.

### Music

Music-related projects, experiments, and notes.

### Garden

Garden notes, seasonal updates, and outdoor projects.

### Notes

General writing, technical notes, odd ideas, experiments, and useful waffle.

### Contact

Ways to reach me and find related profiles/projects.

### Registry

Placeholder for a future product registry system.

## Local Development

Install dependencies:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

Build the site:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Deployment

The site is intended to deploy through Cloudflare Pages from the GitHub repository.

Typical flow:

```bash
git status
git add .
git commit -m "Update site content"
git push
```

Cloudflare handles the deployment after the push.

## Content Approach

The site is not just a digital business card.

It is intended to show:

- What I built
- Why I built it
- What problem it solved
- What tools were used
- What I learned
- Where the code lives
- Whether there are tests, demos, or writeups

The Code section especially should make it obvious that projects are not just screenshots and buzzwords. They should have working repos, useful explanations, and where possible, proper tests.

## Styling Approach

The project currently favors:

- Shared global styles
- Page-specific CSS when useful
- Astro components for repeated layout pieces
- Simple navigation
- Readable project cards
- Clear sections over visual clutter

The goal is personality without turning the site into a haunted carnival flyer.

## Related Projects

Some projects expected to appear on the site:

- [WMATA Backend](https://github.com/SaundersEddie/wmata-be)
- [WMATA Frontend](https://github.com/SaundersEddie/wmata-fe)
- Weather SPA
- Python Sudoku
- Portfolio Playwright Demo
- Social Media Post Generator
- eddiesgames.xyz projects

## Status

Active rebuild in progress.

The immediate goal is to get the replacement site fully structured, deployed, and filled with enough useful content before the old hosting renewal becomes somebody else’s problem.

## Notes

This repo is part portfolio, part workshop, part technical notebook.

Which is another way of saying: yes, there will probably be code, sawdust, drones, gardens, and questionable ideas living near each other.
